## Usage
You can interchange the launch files in this package with the typical launch files you would use for simulating TIAGo; this allows you to use the custom worlds stores in `worlds/`, for example:
```
roslaunch custom_worlds tiago_gazebo.launch robot:=steel public_sim:=true world:=robocup
```
```
roslaunch custom_worlds tiago_mapping.launch robot:=steel public_sim:=true world:=robocup
```
```
roslaunch custom_worlds tiago_navigation.launch robot:=steel public_sim:=true world:=robocup
```

## Credits
This package is based on a historic LASR package.
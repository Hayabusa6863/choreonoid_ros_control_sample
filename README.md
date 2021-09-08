# About this package
This package is to explain how to use choreonoid_ros_control package for your custom robot model.  
Before use this package, you must follow the steps in the url below.
- https://choreonoid.org/ja/manuals/latest/ros/build-choreonoid.html
- https://choreonoid.org/ja/manuals/latest/ros/ros-control/preparation.html#roschoreonoid

The dependent package for this one is ...
- choreonoid
- choreonoid_ros
- choreonoid_ros_control

# How to use
- build this package
```bash:
$ catkin build --this
```

- launch bringup.launch
```bash:
$ roslaunch choreonoid_ros_control_sample bringup.launch
```

- Press the execute button of Choreonoid

- run sinewave_command node
```bash:
$ rosrun choreonoid_ros_control_sample sinewave_command
```
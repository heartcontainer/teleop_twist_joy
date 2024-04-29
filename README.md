teleop_twist_joy [![Build Status](https://travis-ci.org/ros-teleop/teleop_twist_joy.svg?branch=indigo-devel)](https://travis-ci.org/ros-teleop/teleop_twist_joy)
================

Simple joystick teleop for twist robots. See [ROS Wiki](http://wiki.ros.org/teleop_twist_joy)

### Build 
```
mkdir -p ~/ros_ws/src
cd ~/ros_ws/src
git clone git@github.com:heartcontainer/teleop_twist_joy.git -b logitech_f710
cd ~/ros_ws
catkin_make
```

### Run
```
source devel/setup.bash
roslaunch teleop_twist_joy teleop.launch
```

### Usage
- Hold `LB` or `RB`(turbo), then move with joystick
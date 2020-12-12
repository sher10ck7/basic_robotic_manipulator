# basic_robotic_manipulator

### Source the catkin workspace

> source devel/setup.bash

### Launch Gazebo Simulator

>roslaunch gazebo_ros empty_world.launch

### Spawn the robot model

>roslaunch mrm_description spawn.launch

### Control the manipulator

>rostopic pub -1 /mrm/joint2_position_controller/command std_msgs/Float64 "data: 0.7"

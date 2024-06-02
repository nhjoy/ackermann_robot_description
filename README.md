
# Ackermann Robot Description

This repository contains the robot description files for the R2 robot, a model with Ackermann steering, derived from an original URDF provided by Yahboom. It focuses specifically on setting up and running the R2 robot within RViz and Gazebo environments under ROS Melodic.
## Acknowledgements

This project uses a modified version of the URDF originally provided by [Yahboom](http://www.yahboom.net/home). The original files can be found on their [GitHub](https://github.com/YahboomTechnology/ROSMASTER-R2).
## Prerequisites

```bash
  sudo apt-get install ros-melodic-joint-state-publisher-gui
```



## Installation

To use this robot description with ROS Melodi and above, clone this repository into your catkin workspace and compile it:

```bash
  cd ~/catkin_ws/src
  git clone https://github.com/nhjoy/ackermann_robot_description.git
  cd ..
  catkin_make
  source devel/setup.bash
```

## Usage

To launch the robot model in Gazebo:

```bash
  roslaunch ackermann_robot_description gazebo.launch
```

To launch the robot model in RViz:

```bash
  roslaunch ackermann_robot_description rviz.launch
```
## Contribution

Any contributions aimed at improving or extending the project are welcome. Please feel free to fork this repository and submit pull requests.

## Issues

If you encounter any problems or have feedback regarding the `ackermann_robot_description` project, please file an issue on our [GitHub Issues page](https://github.com/nhjoy/ackermann_robot_description/issues). This will help us to continuously improve the project and assist you with your concerns.

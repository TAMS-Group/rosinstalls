# rosinstalls

This repository provides a list of rosinstall files for different setups.
To compile the listed packages in this file, some packages might be required to be installed:

Choose one of the two:
```
source /opt/ros/melodic/setup.bash
source /opt/ros/kinetic/setup.bash
```

This will load the `${ROS_DISTRO}` variable, needed for the next step.

```
sudo apt install ros-"$ROS_DISTRO"-moveit-visual-tools \
ros-"$ROS_DISTRO"-convex-decomposition \
ros-"$ROS_DISTRO"-ivcon \
ros-"$ROS_DISTRO"-moveit \
ros-"$ROS_DISTRO"-controller-interface \
ros-"$ROS_DISTRO"-realtime-tools \
ros-"$ROS_DISTRO"-four-wheel-steering-msgs \
ros-"$ROS_DISTRO"-four-wheel-steering-controller \
ros-"$ROS_DISTRO"-ros-controllers \
ros-"$ROS_DISTRO"-gazebo-ros \
ros-"$ROS_DISTRO"-gazebo-ros-control \
ros-"$ROS_DISTRO"-pr2-common \
ros-"$ROS_DISTRO"-pr2-msgs \
ros-"$ROS_DISTRO"-pr2-description \
ros-"$ROS_DISTRO"-soem \
ros-"$ROS_DISTRO"-socketcan-interface \
libuv-dev \
libcap-dev \
binutils-dev \
libmagick++-dev
```

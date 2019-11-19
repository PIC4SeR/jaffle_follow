> Project: "Person tracking"

> Owner: "Anna Boschi"

> Date: "2019/06"

---
# jaffle_tracking
The Jaffle is an upgrade of the Turtlebot3 waffle using as pc a Jetson Xavier Developer Kit and as camera an Intel Realsense d435i.

The goal of the project is to track and follow a person in an indoor enviroment using a small wheeled rover and suitable sensor to monitor the target person.  

## Hardware requirements
- Turtlebot3 waffle
- Jetson Xavier Developer Kit
- Realsense Camera d435i
- Battery LiPo 4S

## jaffle_tracking files
- The launcher file jaffle_robot.launch launches the realsense d435i camera and both the core and the lidar of the jaffle.
- In the folder nodes there are the files python implemented for doing person tracking with Haarcascade classifier or YOLO (both the code with the control implementation and the one with obstacle avoidance basic implementation).
- In the folder src there are the Haarcascade classifiers used for the person detection.

## ROS Packages for Jaffle
|Version|Kinetic + Ubuntu Xenial| Melodic + Ubuntu Bionic|

## ROBOTIS e-Manual for Jaffle
- [ROBOTIS e-Manual for Jaffle](http://turtlebot3.robotis.com/)
- [Jetson Xavier Developer Kit](https://developer.nvidia.com/embedded/buy/jetson-agx-xavier-devkit)
- [Intel Realsense Depth Camera D435i](https://www.intelrealsense.com/depth-camera-d435i/)

## Open Source related to jaffle_tracking
- [buildLibrealsense2Xavier](https://github.com/jetsonhacks/buildLibrealsense2Xavier)
- [realsense2_camera](https://github.com/IntelRealSense/realsense-ros/tree/development/realsense2_camera)
- [ddynamic_reconfigure](https://github.com/awesomebytes/ddynamic_reconfigure)
- [jaffle_tracking](https://github.com/PIC4SeRCentre/jaffle_tracking)
- [hls_lfcd_lds_driver](https://github.com/ROBOTIS-GIT/hls_lfcd_lds_driver)
- [turtlebot3_msgs](https://github.com/ROBOTIS-GIT/turtlebot3_msgs)
- [rosserial](https://github.com/ros-drivers/rosserial)
- [darknet_ros](https://github.com/leggedrobotics/darknet_ros)


## Documents and Videos to Jaffle
- [Video for Librealsense for Jetson Xavier](https://www.jetsonhacks.com/2019/01/21/intel-realsense-d435i-on-nvidia-jetson-agx-xavier/)
- [Y.O.L.O.](https://pjreddie.com/darknet/yolo/)

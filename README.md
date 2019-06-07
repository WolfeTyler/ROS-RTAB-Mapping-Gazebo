[//]: # (Image References)
[kuka]: ./images/Selection_055.png

# Mapping Gazebo Worlds in ROS with RTAB-Map Project

Real-Time Appearance-Based Mapping (RTAB-Map) is a SLAM algorithm supporting Lidar and RGB-D Graph SLAM. RTAB-Map can be used within a ROS stack to map and localize a mobile robot, handheld Kinect, or lidar device by iteratively detecting loop closures through a hypothesis evaluation and acceptance process. To evaluate RTAB-Map's performance several mapped worlds were navigated by a teleop controlled mobile robot with their output 2D and 3D maps compared with the known Gazebo worlds for accuracy.

![Kuka Gazebo][kuka]

Tasks to be performed:

* Identify the target object on the shelf (placement may be randomized)
* Complete movement towards the target object
* Pickup the target object
* Complete movement towards the drop-off 
* Efficiently place the object at the drop-off

![RTAB-Map_kitchen.gif](https://github.com/WolfeTyler/ROS-RTAB-Mapping-Gazebo/blob/master/images/RTAB-Map_kitchen.gif)

Mapping Mars Rover Gazebo World in ROS with RTAB-Map posted on youtube here:

[![Youtube Video](http://img.youtube.com/vi/RmjkM-wzQw8/0.jpg)](https://youtu.be/RmjkM-wzQw8)


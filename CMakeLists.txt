cmake_minimum_required(VERSION 2.8.3)
project(panther_simulation)

find_package(catkin REQUIRED COMPONENTS 
    panther_description
    gazebo_ros
    gazebo_plugins
    gazebo_ros_control
)

catkin_package()

roslaunch_add_file_check(launch)


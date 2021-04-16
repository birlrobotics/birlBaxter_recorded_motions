cmake_minimum_required(VERSION 3.0.2)
project(birl_recorded_motions)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  rospy
  baxter_interface
)

catkin_python_setup()

catkin_package(
  CATKIN_DEPENDS baxter_interface rospy
)


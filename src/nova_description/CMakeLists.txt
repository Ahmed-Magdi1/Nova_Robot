cmake_minimum_required(VERSION 3.0.2)
project(nova_description)


find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  urdf
)


catkin_package(

)


include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)



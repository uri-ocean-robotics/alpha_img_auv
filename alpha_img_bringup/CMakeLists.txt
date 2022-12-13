cmake_minimum_required(VERSION 3.0.2)
project(alpha_img_bringup)

find_package(catkin REQUIRED COMPONENTS
  alpha_teleop
  alpha_driver
  alpha_img_description
  waterlinked_dvl
)

catkin_package()

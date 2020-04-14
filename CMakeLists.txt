cmake_minimum_required(VERSION 2.8.3)
project(igvc_gazebo)

find_package(catkin REQUIRED COMPONENTS
    gazebo_ros
)

catkin_package(DEPENDS gazebo_ros)

install(DIRECTORY launch scripts urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

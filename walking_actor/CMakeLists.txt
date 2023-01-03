cmake_minimum_required(VERSION 3.5)

project(walking_actor)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY
    launch/
  DESTINATION share/${PROJECT_NAME}/launch
)

install(
  DIRECTORY
    rviz/
  DESTINATION share/${PROJECT_NAME}/rviz
)

ament_package()

cmake_minimum_required(VERSION 3.10)
project(ros2_control_cmake)

# find dependencies
find_package(ament_cmake REQUIRED)

install(
  DIRECTORY cmake
  DESTINATION share/${PROJECT_NAME}
)

ament_package(
  CONFIG_EXTRAS "ros2_control_cmake-extras.cmake"
)

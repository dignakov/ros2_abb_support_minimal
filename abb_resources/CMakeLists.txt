cmake_minimum_required(VERSION 3.5)
project(abb_resources)

find_package(ament_cmake REQUIRED)

install(DIRECTORY urdf
  DESTINATION share/${PROJECT_NAME})

ament_package()

cmake_minimum_required (VERSION 2.8.11)
project (Transformation)

# find_package(Eigen3 REQUIRED)
include_directories("${CMAKE_SOURCE_DIR}/../eigen-3.4.1")

add_executable (Transformation main.cpp)

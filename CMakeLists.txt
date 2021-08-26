cmake_minimum_required(VERSION 3.20)
project(physics_2d_simulation)

set(CMAKE_CXX_STANDARD 14)

find_package(Eigen3 REQUIRED)
MESSAGE( [Main] " EIGEN3_INCLUDE_DIRS = ${EIGEN3_INCLUDE_DIRS}")
# EIGEN3_INCLUDE_DIRS = /usr/include/eigen3
include_directories(${EIGEN3_INCLUDE_DIRS})

add_executable(physics_2d_simulation main.cpp)

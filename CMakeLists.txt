#
# Catkinized package
#

cmake_minimum_required(VERSION 3.5.1)
project(nanoflann)

find_package(catkin REQUIRED)
find_package(Eigen3 REQUIRED)

include_directories(${CMAKE_SOURCE_DIR}/include)
include_directories(${catkin_INCLUDE_DIRS})
include_directories(${EIGEN3_INCLUDE_DIR})

catkin_package(INCLUDE_DIRS ${CMAKE_SOURCE_DIR}/include)

cmake_minimum_required(VERSION 3.21)

project(ranges)

set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} /permissive-")

add_executable(${PROJECT_NAME} ranges.cpp)
cmake_minimum_required(VERSION 3.0)
project(SingleList)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}  -W -Wall -Wfatal-errors -g")
set(CMAKE_BUILD_TYPE Debug)
include_directories(${CMAKE_SOURCE_DIR}/include)
add_executable(main main.cpp)

cmake_minimum_required(VERSION 3.6)
project(WitteckShell)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES myShell.cpp)
add_executable(WitteckShell ${SOURCE_FILES})

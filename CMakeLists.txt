cmake_minimum_required(VERSION 3.3)
project(lab7 CXX)
include(.eecs230/CMakeLists.txt)

add_program(lab7 lab7.cpp)

set(SOURCE_FILES lab7.cpp)
add_executable(lab6 ${SOURCE_FILES})

cmake_minimum_required(VERSION 3.16.3)

project(test_code)

set(CMAKE_CXX_STANDARD 11)

add_executable(test_code main.cpp header.h fun.cpp)
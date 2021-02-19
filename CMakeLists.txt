cmake_minimum_required(VERSION 3.17)
project(ECS C CXX)

set(CMAKE_CXX_STANDARD 20)

add_library(ECS src/library.cpp src/library.h)
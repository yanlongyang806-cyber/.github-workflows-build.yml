cmake_minimum_required(VERSION 3.10)
project(veh_patch_project)

set(CMAKE_CXX_STANDARD 17)

add_library(veh_patch SHARED src/veh_patch_basic.cpp)

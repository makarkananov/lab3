cmake_minimum_required(VERSION 3.12)

project(
        lab3
        VERSION 1.0
        DESCRIPTION "C++ Year 2022 Lab3"
        LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)

include_directories(libs)
include_directories(bin)

add_subdirectory(libs)
add_subdirectory(bin)
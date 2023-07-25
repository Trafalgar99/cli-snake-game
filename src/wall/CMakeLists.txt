cmake_minimum_required(VERSION 3.15)

add_library(wall wall.cpp)

target_include_directories(wall INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

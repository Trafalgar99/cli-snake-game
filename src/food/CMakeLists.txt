cmake_minimum_required(VERSION 3.15)

add_library(food food.cpp)

target_include_directories(food INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(food wall)
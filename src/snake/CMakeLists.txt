cmake_minimum_required(VERSION 3.15)

add_library(snake snake.cpp)

target_include_directories(snake INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(snake wall food)
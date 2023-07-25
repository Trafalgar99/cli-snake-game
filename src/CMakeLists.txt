cmake_minimum_required(VERSION 3.15)

add_subdirectory(food)
add_subdirectory(snake)
add_subdirectory(wall)

add_executable(game game.cpp)

target_link_libraries(game
    PUBLIC
    food snake wall)
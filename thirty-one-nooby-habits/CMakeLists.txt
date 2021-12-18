cmake_minimum_required(VERSION 3.17)
project(NoobyHabits)

set(CMAKE_CXX_STANDARD 20)
add_compile_options(-Wall -Wextra -Wpedantic)

add_executable(NoobyHabits source.cpp)

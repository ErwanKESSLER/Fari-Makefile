cmake_minimum_required(VERSION 3.10)
project(fari)
set(CMAKE_C_STANDARD 99)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -g3")

add_subdirectory(src)
add_subdirectory(test)

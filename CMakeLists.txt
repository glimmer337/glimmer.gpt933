cmake_minimum_required(VERSION 3.15)
project(glimme_gpt933_example LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_POSITION_INDEPENDENT_CODE OFF)

add_executable(main src/main.cpp)

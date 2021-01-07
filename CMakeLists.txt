cmake_minimum_required(VERSION 2.10)
project(SomeProjectName)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

find_package(SDL REQUIRED)
include_directories(${SDL_INCLUDE_DIR})

add_subdirectory(lesson01)

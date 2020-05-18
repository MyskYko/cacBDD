cmake_minimum_required(VERSION 2.8)
project(cacbdd)

file(GLOB FILENAMES ${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp)
add_library(cacbdd ${FILENAMES})
target_include_directories(cacbdd PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/includes)

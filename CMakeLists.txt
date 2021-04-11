cmake_minimum_required(VERSION 3.7)
project(cpplearn)

set(CMAKE_CXX_STANDARD 11)

add_definitions("-g")
set(SOURCE_FILES Server.cpp)
add_executable(APP ${SOURCE_FILES})
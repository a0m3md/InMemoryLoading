cmake_minimum_required(VERSION 3.10)

project(WindowsInMemoryLoader CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(windows-in-memory-loader src/core/main.cpp)

cmake_minimum_required(VERSION 3.28)
project(HelloWorld VERSION 1.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED On)
set(CMAKE_CXX_EXTENSIONS Off)

set(SOURCE main.cpp)
add_executable(HelloWorld ${SOURCE})


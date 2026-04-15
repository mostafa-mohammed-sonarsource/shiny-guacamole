cmake_minimum_required(VERSION 3.0)

project(HelloWorld)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_executable(hello main.cpp)
target_compile_features(hello PRIVATE cxx_std_23)

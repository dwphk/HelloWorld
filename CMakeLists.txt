cmake_minimum_required(VERSION 3.13)

project(main)

add_executable(main main.cpp)

enable_testing()
add_test(NAME main COMMAND main)

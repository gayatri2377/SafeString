cmake_minimum_required(VERSION 3.0.0)
project(test C)

add_executable(test test.c)
target_link_libraries(test m)

cmake_minimum_required(VERSION 3.12)
project(twemproxies C)

set(CMAKE_C_STANDARD 99)
include_directories(src)
add_executable(twemproxies src/nc.c)
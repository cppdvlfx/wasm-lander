cmake_minimum_required(VERSION 3.10)
project(SDL2WasmTest)

set(CMAKE_VERBOSE_MAKEFILE TRUE)
set(CMAKE_C_FLAGS "-s USE_SDL=2")

add_executable(index.html wasmsample.c)

cmake_minimum_required(VERSION 3.28)
project(tommy_and_rene)

set(CMAKE_CXX_STANDARD 17)

add_executable(tommy_and_rene main.cpp
        my_functions.h cmake-build-debug/number_two.cpp)

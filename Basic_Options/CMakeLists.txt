cmake_minimum_required(VERSION 3.15)
project(Basic_Options)

set(CMAKE_CXX_STANDARD 20)

add_executable(Basic_Options main.cpp EuropeanOption.cpp EuropeanOption.h Testing/TestEuropeanOption.cpp)
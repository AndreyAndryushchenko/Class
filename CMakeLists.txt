cmake_minimum_required(VERSION 3.15)
project(classes)

set(CMAKE_CXX_STANDARD 14)

add_executable(classes main.cpp Rational.cpp Rational.hpp)
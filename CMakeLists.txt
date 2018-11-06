cmake_minimum_required(VERSION 3.12)
project(MotorSim)

set(CMAKE_CXX_STANDARD 14)

add_library(MotorSim library.cpp library.h tests/Motor_Emulator_tests.cpp)
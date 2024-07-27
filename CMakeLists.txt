cmake_minimum_required(VERSION 3.5.0)
project(RobotNavigator VERSION 0.1.0 LANGUAGES C CXX)

add_executable(RobotNavigator game.cpp main.cpp robot.cpp)

include(CTest)
enable_testing()


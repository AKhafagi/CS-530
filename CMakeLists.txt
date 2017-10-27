cmake_minimum_required(VERSION 3.6)
project(Programming_Assignment_2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES macroPP.cpp macroPP.h file_parser.h file_parser.cc file_parse_exception.h demoio.s macroPP_error_exception.h)
add_executable(Programming_Assignment_2 ${SOURCE_FILES})
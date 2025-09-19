cmake_minimum_required(VERSION 3.5)
project(cpp-base64 VERSION 1.0.0)
add_library(cpp-base64 STATIC base64.cpp)
target_include_directories(cpp-base64 PUBLIC ${CMAKE_CURRENT_LIST_DIR})
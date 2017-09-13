cmake_minimum_required(VERSION 3.8)
project(avlTree)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp AvlTree.h)
add_executable(avlTree ${SOURCE_FILES})
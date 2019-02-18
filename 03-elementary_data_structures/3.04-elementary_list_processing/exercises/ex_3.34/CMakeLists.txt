cmake_minimum_required(VERSION 3.8)
project(ex_3_34)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        list.h
        list_functions.c
        main.c)

add_executable(ex_3_34 ${SOURCE_FILES})
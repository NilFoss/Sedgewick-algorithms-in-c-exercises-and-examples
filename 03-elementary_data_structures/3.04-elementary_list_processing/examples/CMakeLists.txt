# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)
# 项目信息
project (Demo1)
# 指定生成目标
add_executable(Demo prog_3.11-list_insertion_sort.c)
set(CMAKE_BUILD_TYPE "Debug")
# 指定最低 CMake 版本
cmake_minimum_required(VERSION 3.10)

# 定义项目名称和版本
project(CharSheet VERSION 1.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} main.cc)
# 声明该工程可使用的最低CMake版本
cmake_minimum_required(VERSION 3.23)

# 工程名称
# 我们可以通过"CMAKE_PROJECT_NAME"变量访问该名称
project(Study-CPP)

# ----- 基础知识 -----
add_subdirectory(
        "${PROJECT_SOURCE_DIR}/M01_Overview/C01_HelloWorld"
        "${PROJECT_SOURCE_DIR}/M01_Overview/C01_HelloWorld/cmake-build-debug")

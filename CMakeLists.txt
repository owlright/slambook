# 声明要求的 cmake 最低版本
cmake_minimum_required(VERSION 2.8)

# 声明一个 cmake 工程
project(SLAMBook)

# 设置编译模式
set(CMAKE_PREFIX_PATH "${CMAKE_PREFIX_PATH};${CMAKE_SOURCE_DIR}/3rdparty/install")
add_subdirectory(ch2)
add_subdirectory(ch3)
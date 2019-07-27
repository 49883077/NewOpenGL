#CMake最低版本号要求
cmake_minimum_required (VERSION 2.8)
#项目信息
project (firstWindow)
#指定生成目标

include_directories(E://Learn//NewOpenGL//Includes)
link_directories(E://Learn//NewOpenGL//Libs)

set(SOURCE main.cpp)
add_executable(${PROJECT_NAME} ${SOURCE})
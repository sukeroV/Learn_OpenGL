cmake_minimum_required(VERSION 3.16)
project(learn_opengl)

set(CMAKE_CXX_STANDARD 14)

link_directories("C:/Environments/OpenGL/lib")
include_directories("C:/Environments/OpenGL/include")

add_executable(learn_opengl main.cpp src/glad.c)

target_link_libraries(learn_opengl libglfw3.a)

cmake_minimum_required(VERSION 3.29)
project(ejemplo01)

set(CMAKE_CXX_STANDARD 17)

find_package(fmt)
find_package(glfw3)

add_executable(ejemplo01 main.cpp)

target_link_libraries(ejemplo01 fmt::fmt glfw)

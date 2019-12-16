cmake_minimum_required(VERSION 3.5)
project(create_window VERSION 1.0.0)

add_executable(create_window main.cpp)

target_link_libraries(create_window glfw3 GL m Xrandr Xi X11 Xxf86vm pthread dl Xinerama Xcursor)
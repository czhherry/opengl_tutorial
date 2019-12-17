cmake_minimum_required(VERSION 3.5)
project(using_modern_opengl VERSION 1.0.0)

add_executable(main main.cpp)

target_link_libraries(main glfw3 GLEW GL m Xrandr Xi X11 Xxf86vm pthread dl Xinerama Xcursor)
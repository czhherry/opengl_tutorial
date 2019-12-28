cmake_minimum_required(VERSION 3.5)
project(writing_shader_in_a_file VERSION 1.0.0)

add_executable(main src/main.cpp)

target_link_libraries(main glfw3 GLEW GL m Xrandr Xi X11 Xxf86vm pthread dl Xinerama Xcursor)
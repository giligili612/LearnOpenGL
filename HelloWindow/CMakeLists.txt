cmake_minimum_required(VERSION 3.23)

add_executable(HelloWindow)
target_sources(HelloWindow
  PRIVATE
    HelloWindow.cpp
)
target_link_libraries(HelloWindow
  PRIVATE
  glad
  glfw
)


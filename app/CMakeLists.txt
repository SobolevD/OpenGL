cmake_minimum_required (VERSION 3.8)

project("App" CXX)

add_executable(${PROJECT_NAME} "main.cpp")

target_link_libraries(${PROJECT_NAME} glew_s glfw)

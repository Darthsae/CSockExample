cmake_minimum_required(VERSION 3.5.0)
project(CSockExample VERSION 0.1.0 LANGUAGES C)

add_subdirectory(CSockLib)
add_executable(CSockExample src/main.c)

target_link_libraries(CSockExample CSockLib)
cmake_minimum_required(VERSION 3.14)

add_executable(executable main.cpp)

target_link_libraries(executable PRIVATE library)
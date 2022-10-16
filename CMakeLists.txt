cmake_minimum_required(VERSION 3.14)
project(cmake-template VERSION 0.0.1)

set(CMAKE_CXX_STANDARD 20)

include(CTest)
enable_testing()
include(CPack)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})

add_subdirectory(library)
add_subdirectory(executable)

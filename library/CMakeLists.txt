cmake_minimum_required(VERSION 3.14)

set(SOURCE_FILES
    include/lib.h
    src/lib.cpp
)

add_library(library STATIC ${SOURCE_FILES})
cmake_minimum_required(VERSION 3.9)
project(avm)

set(CMAKE_CXX_STANDARD 11)

set(SOURCES
        sources/main.cpp
        )

add_executable(avm ${SOURCES})
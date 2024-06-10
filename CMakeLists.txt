cmake_minimum_required(VERSION 3.28)
project(Rubixcubesolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(Rubixcubesolver main.cpp
        RubiksCube.cpp
        RubiksCube.h
        RubiksCube3Darray.cpp
)

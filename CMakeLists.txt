cmake_minimum_required(VERSION 3.28)
project(Rubixcubesolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(Rubixcubesolver main.cpp
        Model/RubiksCube.cpp
        Model/RubiksCube.h
        Model/RubiksCube3dArray.cpp
        Model/RubiksCube1dArray.cpp
        Solver/BFSSolver.h
        Solver/DFSSolver.h
        Solver/IDDFSSolver.h

)

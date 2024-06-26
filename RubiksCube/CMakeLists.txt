cmake_minimum_required(VERSION 3.28)
project(RubiksCube)

set(CMAKE_CXX_STANDARD 14)

add_executable(RubiksCube
        main.cpp
        Model/PatternDatabase/RubiksCube.cpp
        Model/PatternDatabase/RubiksCube.h
        Model/PatternDatabase/RubiksCube1dArray.cpp
        Model/PatternDatabase/RubiksCube3dArray.cpp
        Model/PatternDatabase/RubiksCubeBitboard.cpp
        Model/PatternDatabases/CornerDBMaker.cpp
        Model/PatternDatabases/CornerDBMaker.h
        Model/PatternDatabases/CornerPatternDatabase.cpp
        Model/PatternDatabases/CornerPatternDatabase.h
        Model/PatternDatabases/math.cpp
        Model/PatternDatabases/math.h
        Model/PatternDatabases/NibbleArray.cpp
        Model/PatternDatabases/NibbleArray.h
        Model/PatternDatabases/PatternDatabase.cpp
        Model/PatternDatabases/PatternDatabase.h
        Model/PatternDatabases/PermutationIndexer.h
        Model/Solver/BFSSolver.h
        Model/Solver/DFSSolver.h
        Model/Solver/IDAstarSolver.h
        Model/Solver/IDDFSSolver.h
)

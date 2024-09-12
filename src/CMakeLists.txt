cmake_minimum_required(VERSION 3.27)
project(FileViewerProgram)

set(CMAKE_CXX_STANDARD 17)

add_executable(FileViewerProgram main.cpp
        Buffer.cpp
        Buffer.h
        FileViewer.cpp
        FileViewer.h)

cmake_minimum_required(VERSION 3.26)
project(Parallel_Programming_Assignments)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)

add_executable(Parallel_Programming_Assignments
        include/wb.h
        MP0/MP0.cu
        MP1/MP1.cu
        MP2/MP2.cu
        MP3/MP3.cu
        MP4/MP4.cu)

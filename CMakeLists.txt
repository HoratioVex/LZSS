cmake_minimum_required(VERSION 3.13)  # CMake version check
project(LZSS_Ref)               # Create project "simple_example"
#set(CMAKE_CXX_STANDARD 14)            # Enable c++14 standard

# Add main.cpp file of the project root directory as a source file
set(SOURCE_FILES 2022/lzss.cpp)
set(RUNTIME_OUTPUT_DIRECTORY Build/)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(LZSS_Ref ${SOURCE_FILES})
add_executable(LZSS_Org 1989/LZSS.C)

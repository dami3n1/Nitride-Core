cmake_minimum_required(VERSION 3.15)
project(nitride)

# Use C++17
set(CMAKE_CXX_STANDARD 17)

# Collect all source files
file(GLOB_RECURSE SOURCES "src/*.cpp")

# Create a static library
add_executable(${PROJECT_NAME} ${SOURCES})
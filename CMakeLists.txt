cmake_minimum_required(VERSION 3.10)

# Set the project name and version
project(RayTracingWeekend VERSION 1.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include the header files directory
include_directories(include)

# Add the executable
add_executable(RayTracingWeekend src/main.cpp)

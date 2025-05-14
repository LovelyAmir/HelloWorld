cmake_minimum_required(VERSION 3.10)

# Define the project name
project(HelloWorld)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable and specify the source file
add_executable(HelloWorld Helloworld.cpp)
# Configure CMake 
cmake_minimum_required(VERSION 3.6)

# Configure project
project(CreateRTH)

# Add source files
set(SOURCE_FILES src/hello_world.cpp)
#set(HEADER_FILES src/hello_world.h) 

# Add executables
add_executable(HelloWorld ${SOURCE_FILES})

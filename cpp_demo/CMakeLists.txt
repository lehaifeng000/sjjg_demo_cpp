#CMakeLists.txt
cmake_minimum_required(VERSION 2.3.0)
project(cpp_demo)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")

SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin) 

add_executable(hello ${SOURCES})
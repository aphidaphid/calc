cmake_minimum_required(VERSION 4.0)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_FLAGS    "-Wfatal-errors")

project(calc)

add_executable(${PROJECT_NAME} src/main.cpp src/token.cpp src/lexer.cpp)

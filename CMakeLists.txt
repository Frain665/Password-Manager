cmake_minimum_required(VERSION 3.10)
project(PasswordManager)

set(PROJECT_NAME MyProject)

set(CMAKE_CXX_STANDARD 11)

set(SOURCES
src/main.cpp

)

add_executable(src ${SOURCES})
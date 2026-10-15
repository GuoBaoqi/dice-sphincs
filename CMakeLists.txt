cmake_minimum_required(VERSION 3.20)
project(dice-sphincs LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(dice-sphincs
    src/main.cpp
)

target_include_directories(dice-sphincs PRIVATE include)
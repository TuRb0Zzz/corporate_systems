cmake_minimum_required(VERSION 3.22) 

project(PrintWorld LANGUAGES CXX)


set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(app 
    main.cpp
    hello.cpp
    hello.h
)


target_include_directories(app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})
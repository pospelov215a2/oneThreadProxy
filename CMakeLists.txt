cmake_minimum_required(VERSION 3.6)
project(oneThreadProxy)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
        main.cpp
        connection_list.h cache_list.h data_handler.h header.h)
add_executable(oneThreadProxy ${SOURCE_FILES})
cmake_minimum_required(VERSION 3.29)
project(redy)

set(CMAKE_CXX_STANDARD 20)

add_executable(redy
        client.c
        server.c)

cmake_minimum_required(VERSION 3.19)
project(AES)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(AES
        main.c src/mode.c src/mode.h src/AES.h src/AES.c src/utils.c src/utils.h)
cmake_minimum_required(VERSION 3.15)
project(canny)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(out)

add_executable(canny
        canny.c
        CMakeLists.txt
        dc_image.c
        dc_image.h
        make.bat
        stb_image.h
        stb_image_write.h
        sun.jpg)

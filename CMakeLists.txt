cmake_minimum_required(VERSION 3.16)
project(cs106L_HashMap)

set(CMAKE_CXX_STANDARD 17)

include_directories(.)

add_executable(main
        hashmap.cpp
        hashmap.h
        hashmap_iterator.h
        main.cpp
        test_settings.cpp
        tests.cpp)

cmake_minimum_required(VERSION 3.23)
project(use_student)

set(CMAKE_CXX_STANDARD 14)

set(SRC
        main.cpp
        src/student.cpp)

add_executable(use_student ${SRC})

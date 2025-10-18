cmake_minimum_required(VERSION 4.0)
project(week_8_homework_KGhim7)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(week_8_homework_KGhim7
        ArrayStack.hpp
        ArrayStack.tpp
        homework.cpp
        LinkedListStack.hpp
        LinkedListStack.tpp
        Stack.hpp
        StackFactory.hpp)

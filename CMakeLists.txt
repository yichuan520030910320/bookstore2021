cmake_minimum_required(VERSION 3.17)
project(code)

set(CMAKE_CXX_STANDARD 14)

add_executable(bookstore2021 main.cpp
        BookStore.h
        UnrolledLinkedList.h
        UnrolledLinkedList.cpp)
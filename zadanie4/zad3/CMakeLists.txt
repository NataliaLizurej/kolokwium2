cmake_minimum_required(VERSION 3.10)
project(nazwa1)
include_directories(include)
add_executable(nazwa1 src/libtest.cpp)
add_library(Student SHARED src/Student.cpp)
target_link_libraries(nazwa1 Student)


project(naive_bayes)

cmake_minimum_required (VERSION 3.5)

add_definitions(-std=c++11 -O3)

set(CXX_FLAGS "-w2")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")

set(sources main.cpp classifier.cpp)

add_executable(a ${sources})



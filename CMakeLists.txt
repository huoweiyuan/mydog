cmake_minimum_required(VERSION 3.22)
project(mydog)
add_subdirectory(y)

SET(TESTING_SRC )
add_executable(mydogd main.cc ${TESTING_SRC})
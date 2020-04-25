cmake_minimum_required(VERSION 3.14)

set(CMAKE_C_STANDARD 11)

message(STATUS "Building CPace library...")

ADD_LIBRARY(cpace STATIC
	src/cpace.c)

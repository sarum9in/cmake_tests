cmake_minimum_required(VERSION 3.0)

project(test_)

message("1: ${MYVAR}")
#include(b.cmake OPTIONAL)
set(MYVAR OFF)
message("2: ${MYVAR}")
set(MYVAR ON CACHE BOOL "set1")
message("3: ${MYVAR}")
set(MYVAR ON CACHE BOOL "set2")
message("4: ${MYVAR}")

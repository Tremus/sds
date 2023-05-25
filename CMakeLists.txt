cmake_minimum_required(VERSION 3.15)
project(sds VERSION 2.0.0 LANGUAGES C)
set(CMAKE_C_STANDARD 99)

add_library(sds STATIC sds.c)

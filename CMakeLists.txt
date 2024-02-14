cmake_minimum_required(VERSION 3.5)
project(ce_profiler)

add_library(ce_profiler INTERFACE)


target_include_directories(ce_profiler INTERFACE include "${CMAKE_CURRENT_SOURCE_DIR}/")

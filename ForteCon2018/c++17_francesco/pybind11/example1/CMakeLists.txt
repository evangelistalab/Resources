cmake_minimum_required (VERSION 3.0)
set (CMAKE_CXX_STANDARD 17)

project (example1)
add_subdirectory(pybind11)

pybind11_add_module(example1 example1.cc)

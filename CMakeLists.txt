cmake_minimum_required(VERSION 3.27)

project(cpp_template)

set(CMAKE_CXX_STANDARD 20)

include(cmake/helpers.cmake)

add_subdirectory(lib)
add_subdirectory(cmd)
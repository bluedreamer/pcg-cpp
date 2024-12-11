cmake_minimum_required(VERSION 3.28)
project(pcg-cpp)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_EXPORT_COMPILE_COMMANDS TRUE)

include_directories(include)
add_library(pcg-cpp INTERFACE
        include/pcg_uint128.hpp
        include/pcg_random.hpp
        include/pcg_extras.hpp)

add_subdirectory(sample)
add_subdirectory(test-high)
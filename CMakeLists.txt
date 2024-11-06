cmake_minimum_required(VERSION 3.29)
project(untitled16)

set(CMAKE_CXX_STANDARD 20)

add_executable(untitled16 main.cpp)
include(FetchContent)
FetchContent_Declare(
        fmt
        GIT_REPOSITORY https://github.com/fmtlib/fmt.git
        GIT_TAG        7.1.3
)

FetchContent_MakeAvailable(fmt)
cmake_minimum_required(VERSION 3.15)
project(my_project C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)

set(CMAKE_C_COMPILER gcc)

add_compile_options(-Wall -Werror)

include_directories(${CMAKE_SOURCE_DIR}/include)
file(GLOB SOURCES "src/*.c")
add_executable(my_project ${SOURCES})

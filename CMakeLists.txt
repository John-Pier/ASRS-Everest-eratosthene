cmake_minimum_required(VERSION 3.22)
project(task2-eratosthene)

set(CMAKE_CXX_STANDARD 14)
set(TARGET_SRC task-2-er.cpp)
include_directories(.)

add_executable(task2-eratosthene task-2-er.cpp)
target_link_libraries(task2-eratosthene -lcurl)

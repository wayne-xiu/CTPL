cmake_minimum_required(VERSION 3.10)

project(CTPL_example)

add_executable(example example.cpp)
target_include_directories(example PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/../include)

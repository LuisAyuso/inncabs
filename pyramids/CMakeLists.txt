project(pyramids CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)

add_executable(pyramids ${module_srcs})
target_link_libraries(pyramids ${CMAKE_THREAD_LIBS_INIT})

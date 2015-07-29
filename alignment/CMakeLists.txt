project(alignment CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)


add_executable(alignment ${module_srcs})
target_link_libraries(alignment ${CMAKE_THREAD_LIBS_INIT})


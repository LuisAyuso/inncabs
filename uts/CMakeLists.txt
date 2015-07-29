project(uts CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)


add_executable(uts ${module_srcs})
target_link_libraries(uts ${CMAKE_THREAD_LIBS_INIT})

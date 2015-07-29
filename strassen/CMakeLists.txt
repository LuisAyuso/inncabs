project(strassen CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)


add_executable(strassen ${module_srcs})
target_link_libraries(strassen ${CMAKE_THREAD_LIBS_INIT})

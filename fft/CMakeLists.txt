project(fft CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)

add_executable(fft ${module_srcs})
target_link_libraries(fft ${CMAKE_THREAD_LIBS_INIT})

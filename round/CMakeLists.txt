project(round CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)


add_executable(round ${module_srcs})
#target_include_directories(fft ${inncabs_includes})


project(floorplan CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp *.c)

add_executable(floorplan ${module_srcs})
target_link_libraries(floorplan ${CMAKE_THREAD_LIBS_INIT})

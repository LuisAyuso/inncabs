project(fib CXX)

cmake_minimum_required(VERSION 2.8)

file(GLOB_RECURSE module_srcs *.cpp)

add_executable(fib ${module_srcs})
target_link_libraries(fib ${CMAKE_THREAD_LIBS_INIT})

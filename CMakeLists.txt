project(inncabs CXX)

cmake_minimum_required(VERSION 2.8)

# find pthreads
ENABLE_LANGUAGE(C)
FIND_PACKAGE(Threads)

#set (inncabs_includes "./include")
include_directories("./include")

set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_subdirectory(fft)
add_subdirectory(alignment)
add_subdirectory(fib)
add_subdirectory(floorplan)
add_subdirectory(health)
add_subdirectory(intersim)
add_subdirectory(nqueens)
add_subdirectory(pyramids)
add_subdirectory(qap)
add_subdirectory(round)
add_subdirectory(sort)
add_subdirectory(sparselu)
add_subdirectory(strassen)
add_subdirectory(uts)


if (APPLE)
    cmake_minimum_required(VERSION 3.20)
    set(CMAKE_CXX_STANDARD 20)
elseif (LINUX)
    cmake_minimum_required(VERSION 3.10)
endif ()

project(Christmas_Class)
add_executable(ep150 ep150.cpp)
add_executable(ep48 ep48.cpp)
add_executable(ep49 ep49.cpp)
add_executable(ep184 ep184.cpp)
add_executable(exercise2 exercise.cpp)
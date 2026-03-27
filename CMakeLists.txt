cmake_minimum_required(VERSION 3.20)
project(Aufgabenblatt1)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(DOCTEST_DIRECTORY doctest)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/external/${DOCTEST_DIRECTORY})

#check for CMakeLists.txt files in subdirectory source (where your applications are)
add_subdirectory(source)

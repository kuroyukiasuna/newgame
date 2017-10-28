cmake_minimum_required(VERSION 3.7)
project(newgame)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp landscape.cpp landscape.h map.cpp map.h player.cpp player.h textdisplay.cpp textdisplay.h)
add_executable(newgame ${SOURCE_FILES})
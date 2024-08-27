cmake_minimum_required(VERSION 3.5)
project(Tetris)

add_library(MyLib 
sources/designe.cpp 
sources/designe.h 
sources/game.cpp 
sources/game.h
)

add_executable(Tetris sources/main.cpp resources/tetris.rc)

target_link_libraries(Tetris PUBLIC MyLib)
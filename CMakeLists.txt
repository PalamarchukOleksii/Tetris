cmake_minimum_required(VERSION 3.5)
project(Tetris)

add_library(MyLib 
sources/designe.cpp 
sources/designe.h 
sources/game.cpp 
sources/game.h
)

add_executable(MyTetris sources/main.cpp)

target_link_libraries(MyTetris PUBLIC MyLib)
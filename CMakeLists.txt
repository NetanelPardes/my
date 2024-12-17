cmake_minimum_required(VERSION 3.10)

project(tictactoe)

set(CMAKE_CXX_STANDARD 14)

add_executable(TicTacToe main.cpp TicTacToe.cpp Board.cpp)

cmake_minimum_required(VERSION 3.24)
project(structures.lab C)

set(CMAKE_C_STANDARD 11)

add_executable(structures structures/structures.c structures/Header.h structures/Source.c)

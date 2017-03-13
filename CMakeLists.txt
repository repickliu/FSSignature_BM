cmake_minimum_required(VERSION 3.6)
project(FSSignature_BM)

set(CMAKE_CXX_STANDARD 11)

link_libraries(crypto)

set(SOURCE_FILES main.cpp)
add_executable(FSSignature_BM ${SOURCE_FILES})
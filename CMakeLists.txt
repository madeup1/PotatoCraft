cmake_minimum_required(VERSION 3.5)

project (PotatoCraft)

set(CMAKE_C_COMPILER clang)
set(CMAKE_CXX_COMPILER clang++)

file(GLOB_RECURSE SOURCES "src/*.cpp")

add_executable(PotatoCraft ${SOURCES})

target_include_directories(PotatoCraft PRIVATE "src/*.h")
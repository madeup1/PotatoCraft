cmake_minimum_required(VERSION 3.5)

project (PotatoCraft)

file(GLOB_RECURSE SOURCES "src/*.cpp")

add_executable(PotatoCraft ${SOURCES})

target_include_directories(PotatoCraft PRIVATE "src/*.h")
cmake_minimum_required(VERSION 3.7)
project(WoW_Addon_Updater)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES src/main.cpp)

add_executable(WoW_Addon_Updater ${SOURCE_FILES})

cmake_minimum_required(VERSION 3.30)

project(qdrive)

add_library(qdrive INTERFACE)

target_sources(qdrive INTERFACE QDrive.cpp)

target_include_directories(qdrive INTERFACE
        ./
        ./base_classes
)
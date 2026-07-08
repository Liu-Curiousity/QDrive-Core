cmake_minimum_required(VERSION 3.30)

project(QDrive)

add_library(QDrive OBJECT QDrive.cpp)

target_include_directories(QDrive PUBLIC
        ./
        ./base_classes
)

target_link_libraries(QDrive
        PID
)
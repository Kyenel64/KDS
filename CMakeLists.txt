cmake_minimum_required(VERSION 3.27)

project ("KDS")

set (SrcFiles
    "main.cpp"
    "DataStructures/Set.h" "DataStructures/Set.cpp")

add_executable(${PROJECT_NAME} ${SrcFiles})

set_property(TARGET ${PROJECT_NAME} PROPERTY CXX_STANDARD 20)

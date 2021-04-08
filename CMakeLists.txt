cmake_minimum_required(VERSION 3.18)

project(root, VERSION 0.0.1)

set(CMAKE_C_STANDARD 11)
set(C_STANDARD_REQUIRED True)
set(LANGUAGE C)

add_subdirectory(${PROJECT_SOURCE_DIR}/src/SimpleGui)
add_subdirectory(${PROJECT_SOURCE_DIR}/src/Sandbox)

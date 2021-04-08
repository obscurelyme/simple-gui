cmake_minimum_required(VERSION 3.18)

project(Sandbox)

set(CMAKE_C_STANDARD 11)
set(C_STANDARD_REQUIRED True)
set(LANGUAGE C)

add_executable(Sandbox main.c)

target_link_libraries(Sandbox PUBLIC SimpleGui)
target_include_directories(Sandbox PUBLIC "${PROJECT_BINARY_DIR}" "${PROJECT_SOURCE_DIR}/../SimpleGui")

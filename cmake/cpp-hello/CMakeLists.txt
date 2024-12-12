cmake_minimum_required(VERSION 3.26)

project(cmake-cpp-hello CXX)

aux_source_directory(. SRCS_MAIN)
add_executable(${PROJECT_NAME} ${SRCS_MAIN})


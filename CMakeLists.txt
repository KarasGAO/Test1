cmake_minimum_required(VERSION 3.30)

set(PROJECT_NAME_STR Test1)

include_directories(${CMAKE_CURRENT_DIR}/src)

file(GLOB PATH_STR ${CMAKE_CURRENT_DIR}/src/*.cpp ${CMAKE_CURRENT_DIR}/src/*.hpp)

add_executable(${PROJECT_NAME_STR} ${PATH_STR}src/main.cpp)
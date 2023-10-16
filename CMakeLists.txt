cmake_minimum_required(VERSION 3.5)

project (ANIMALFARM)
set (AF_VERSION_MAJOR 1)
set (AF_VERSION_MINOR 0)

set (EXECUTABLE_NAME "animalfarm")

#include_directories ("${AF_BINARY_DIR}")
#add_subdirectory("src")
#include_directories ("${AF_BINARY_DIR}/src")
#link_directories ("${AF_BINARY_DIR}/src")

add_executable(${EXECUTABLE_NAME} src/main.cpp)

#set(CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}" ${CMAKE_MODULE_PATH})
#find_package(SFML 2.0 REQUIRED system window graphics network audio)

#target_link_libraries(${EXECUTABLE_NAME} ${SFML_LIBRARIES})

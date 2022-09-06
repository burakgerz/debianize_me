cmake_minimum_required(VERSION 3.8)

project(HelloCMake VERSION 0.0.1)

add_executable(hello-cmake main.c)

install(TARGETS hello-cmake DESTINATION bin)

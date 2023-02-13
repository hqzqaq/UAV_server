cmake_minimum_required(VERSION 3.22.1)
project(UAV_server)

set(CMAKE_CXX_STANDARD 11)

add_executable(UAV_server main.cpp WebsocketClient.cpp WebsocketClient.h)

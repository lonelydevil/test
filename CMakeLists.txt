cmake_minimum_required(VERSION 3.15)

project(test)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(test)

target_sources(test PRIVATE
	Sources/main.c
	Sources/custom.c)

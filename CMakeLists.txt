cmake_minimum_required(VERSION 3.22.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(STDEXEC LANGUAGES CXX)

# Define the main library
add_library(stdexec INTERFACE)
target_include_directories(stdexec
	INTERFACE .)
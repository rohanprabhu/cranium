cmake_minimum_required (VERSION 2.6)
include_directories("${PROJECT_SOURCE_DIR}/deps/v8/include")
project (cranium)
add_executable(cranium main.cpp)

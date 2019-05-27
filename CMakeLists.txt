cmake_minimum_required(VERSION 3.14)
project(YAS)

add_library(yas INTERFACE)
target_compile_features(yas INTERFACE cxx_std_11)
target_include_directories(yas INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)

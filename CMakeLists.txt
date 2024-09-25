# CMakeLists.txt --- CMake project settings
##############################################################################

# CMake minimum version
cmake_minimum_required(VERSION 3.6)

# project name and language
project(MSha256 CXX)

# libMSha256.a
add_library(MSha256 STATIC MSha256.cpp)

##############################################################################


cmake_minimum_required(VERSION 3.7)
project(Hello)
add_executable(hello hello.cpp)
find_package(cdep-dependencies REQUIRED)
add_cdep_boost_dependency(hello)

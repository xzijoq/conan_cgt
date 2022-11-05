cmake_minimum_required(VERSION 3.25)
project(cgt VERSION 1.0 LANGUAGES C CXX)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_library(cgt src/cgt.cpp)
target_include_directories(cgt PUBLIC include)



set_target_properties(cgt PROPERTIES PUBLIC_HEADER "include/cgt.h")
install(TARGETS cgt)


#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x


#add_subdirectory(tests)
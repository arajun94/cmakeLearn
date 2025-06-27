cmake_minimum_required(VERSION 3.25)

project(cmakeLearn1 C)

add_subdirectory(src)

add_executable(cmakeLearn1 main.c)

target_link_libraries(cmakeLearn1 PRIVATE
    fizzBuzz
)
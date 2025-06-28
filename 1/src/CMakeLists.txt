add_library(fizzBuzz STATIC)

target_sources(fizzBuzz
    PRIVATE
        fizzBuzz.c
)

target_include_directories(fizzBuzz
    INTERFACE
        ${CMAKE_CURRENT_LIST_DIR}
)
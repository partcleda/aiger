add_library(aiger STATIC
    aiger.c
    simpaig.c
)

target_include_directories(aiger PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
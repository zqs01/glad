add_library(af_glad_interface INTERFACE)

target_include_directories(af_glad_interface
    INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/include
    )

target_sources(af_glad_interface
    INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/src/glad.c
    )

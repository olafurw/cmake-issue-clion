add_executable(bug main.cpp)
target_link_libraries(bug PUBLIC libbug)

set_target_properties(bug
        PROPERTIES
        RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/bin"
)

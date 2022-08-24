file(GLOB_RECURSE sources CONFIGURE_DEPENDS "*.cpp" "*.hpp")

add_library(libbug ${sources})

target_include_directories(libbug PUBLIC include)

project(cmake_wrapper)

set(CMAKE_VERBOSE_MAKEFILE TRUE)

include("${CMAKE_BINARY_DIR}/conanbuildinfo.cmake")
conan_basic_setup()

add_subdirectory("tulip")

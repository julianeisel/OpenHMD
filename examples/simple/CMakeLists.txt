project (simple)
include_directories(${CMAKE_BINARY_DIR}/include)
link_directories(${CMAKE_BINARY_DIR})
link_libraries (openhmd m)
add_executable(simple simple.c)
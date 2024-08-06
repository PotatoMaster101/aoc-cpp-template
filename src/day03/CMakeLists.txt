configure_input_file(${CMAKE_CURRENT_SOURCE_DIR}/input.txt)
cmake_path(GET CMAKE_CURRENT_SOURCE_DIR STEM day)
add_executable(${day} main.cpp)

cmake_minimum_required(VERSION 3.20) # 4.x is a bit high so we downgrade
project(cmake_demo)

set(CMAKE_CXX_STANDARD 20)

# clean code - delegate to subfolders:

# one for the library
add_subdirectory(src)

# one for the applications
add_subdirectory(app)

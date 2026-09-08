
# A CMake project can have multiple targets

add_executable(cmake_demo main.cpp)
target_link_libraries(cmake_demo PUBLIC hellolib)

add_executable(cmake_demo2 main2.cpp)
target_link_libraries(cmake_demo2 PUBLIC hellolib)
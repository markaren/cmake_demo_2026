
add_library(hellolib greet.cpp)

# any targets linking against hellolib inherits this include path
target_include_directories(hellolib PUBLIC "${CMAKE_SOURCE_DIR}/include")
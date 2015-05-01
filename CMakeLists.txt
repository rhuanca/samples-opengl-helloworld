cmake_minimum_required (VERSION 2.8)
project (sample-glfw)


#include the subdirectory containing our libs
# add_subdirectory (src)

#include_directories(../glfw/include)
#link_directories(../glfw/src)

add_executable (sample-glfw sample.cpp)

target_link_libraries (sample-glfw glfw GL)


# install (TARGETS CMakeHelloWorld DESTINATION bin)
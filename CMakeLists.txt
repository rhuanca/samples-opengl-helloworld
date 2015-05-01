cmake_minimum_required (VERSION 2.8)
project (CMakeHelloWorld)


#include the subdirectory containing our libs
# add_subdirectory (src)
# include_directories(Hello)
#indicate the entry point for the executable
add_executable (CMakeHelloWorld sample sample.cpp)

# Indicate which libraries to include during the link process.
# target_link_libraries (CMakeHelloWorld Hello)

# install (TARGETS CMakeHelloWorld DESTINATION bin)
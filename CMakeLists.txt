cmake_minimum_required(VERSION 3.16)
project(udp_kernel_timestamp_example
        VERSION 0.1
        DESCRIPTION "Kernel timestamping example"
        LANGUAGES CXX)


set(CMAKE_CXX_STANDARD 20)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_subdirectory(sender)
add_subdirectory(receiver)

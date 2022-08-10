cmake_minimum_required(VERSION 3.12)

project(00-install C CXX)

set(CMAKE_POSITION_INDEPENDENT_CODE TRUE)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

find_package(Boost CONFIG REQUIRED)
find_package(Microsoft.GSL CONFIG REQUIRED)

# look for libp2p in OS
find_package(libp2p CONFIG REQUIRED)

add_executable(main main.cpp)
target_link_libraries(main
    p2p::p2p_multiaddress
    )

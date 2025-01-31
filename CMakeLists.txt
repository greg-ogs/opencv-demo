cmake_minimum_required(VERSION 3.30)
project(opencv-demo)

set(CMAKE_CXX_STANDARD 23)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(opencv-demo main.cpp)

target_link_libraries(opencv-demo ${OpenCV_LIBS})
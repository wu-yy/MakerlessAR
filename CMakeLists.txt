cmake_minimum_required(VERSION 3.12)
project(MakerlessAR)

find_package(OpenCV)
set(CMAKE_CXX_STANDARD 11)

include_directories(${OpenCV_INCLUDE_DIRS})
# add_executable(untitled2 main.cpp)
add_executable(MakerlessAR main.cpp)

target_link_libraries(MakerlessAR ${OpenCV_LIBS})
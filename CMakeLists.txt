cmake_minimum_required(VERSION 3.5)

project(qt5dp-13-1 LANGUAGES CXX)

set(CMAKE_INCLUDE_CURRENT_DIR ON)

set(CMAKE_AUTOUIC ON)
set(CMAKE_AUTOMOC ON)
set(CMAKE_AUTORCC ON)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(Qt5Core)

add_executable(qt5dp-13-1
  main.cpp
)
target_link_libraries(qt5dp-13-1 Qt5::Core)

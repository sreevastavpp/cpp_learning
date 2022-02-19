cmake_minimum_required(VERSION 3.14)

PROJECT(olas VERSION 1.0)

add_executable(olas src/main.cc)

find_package(fmt REQUIRED)

target_link_libraries(olas
  PRIVATE
    fmt::fmt)
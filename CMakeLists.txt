cmake_minimum_required(VERSION 3.16)

project(littleFS)

file(GLOB littlefsSrcs *.c)
add_library(littleFS ${littlefsSrcs})

target_include_directories(littleFS PUBLIC .)
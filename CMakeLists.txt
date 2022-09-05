cmake_minimum_required(VERSION 3.16)

project(littleFS)

add_library(littleFS 
    lfs.c
    lfs_util.c
)

target_include_directories(littleFS PUBLIC .)
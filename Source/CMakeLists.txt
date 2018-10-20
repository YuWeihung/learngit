cmake_minimum_required (VERSION 3.10)

project (Hello)

aux_source_directory(. DIR_SRCS)

add_executable(hello ${DIR_SRCS})

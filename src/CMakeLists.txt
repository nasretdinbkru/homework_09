cmake_minimum_required(VERSION 3.10)

SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")

#project(topk_words CXX)
# add_executable(topk_words  topk_words.cpp)

project(topk_words_m CXX)
add_executable(topk_words_m  topk_words_m.cpp)
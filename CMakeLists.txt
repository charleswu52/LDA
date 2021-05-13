cmake_minimum_required(VERSION 3.19)
project(LDA)

set(CMAKE_CXX_STANDARD 11)

add_executable(LDA test/entry.cpp include/LevenshteinDFA.h include/LevenshteinNFA.h include/Trie.h src/LevenshteinDFA.cpp src/LevenshteinNFA.cpp src/Trie.cpp)
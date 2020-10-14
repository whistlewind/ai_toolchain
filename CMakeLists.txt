cmake_minimum_required(VERSION 3.17)
project(ai_toolchain)

set(CMAKE_CXX_STANDARD 11)

add_executable(ai_toolchain main.cpp aes/AES.cpp aes/AES.h aes/AesEncryptor.cpp aes/AesEncryptor.h)
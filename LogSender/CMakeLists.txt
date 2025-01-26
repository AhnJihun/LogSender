project(LogSender)

cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 11)

include_directories(Header)

file(GLOB HEADER_FILES Header/*.h)
file(GLOB SOURCE_FILES Source/*.cpp)

add_executable(LogSender ${HEADER_FILES} ${SOURCE_FILES})
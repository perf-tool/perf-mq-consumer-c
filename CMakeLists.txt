cmake_minimum_required(VERSION 3.22)
project(perf-mq-consumer-c)

set(CMAKE_CXX_STANDARD 23)
set(TARGET perf-mq-consumer-c)

FILE(GLOB Sources *.h *.c)
add_executable(${TARGET} ${Sources})

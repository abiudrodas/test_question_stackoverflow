PROJECT(Test)
CMAKE_MINIMUM_REQUIRED(VERSION 3.0)

INCLUDE_DIRECTORIES( ${CMAKE_SOURCE_DIR}
                     include)
SET(SRC main.cpp)

add_executable(testexception ${SRC})



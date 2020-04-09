# Copyright (C) 2010 Johannes Weißl <jargon@molb.org>
# License: MIT License
# URL: https://github.com/weisslj/cpp-optparse

# CMake script and other modifications
# Copyright (C) 2020 EM Microelectronic
# URL: https://github.com/emmicro-us/cpp-optparse

CMAKE_MINIMUM_REQUIRED(VERSION 2.6.0)

PROJECT(OptionParser)

ADD_LIBRARY(${PROJECT_NAME} STATIC ${PROJECT_NAME}.cpp)

TARGET_INCLUDE_DIRECTORIES(${PROJECT_NAME} PUBLIC .)

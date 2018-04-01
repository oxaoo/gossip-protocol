cmake_minimum_required(VERSION 3.10)
project(mp1_idea)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(mp1_idea
        Application.cpp
        Application.h
        EmulNet.cpp
        EmulNet.h
        Grader.sh
        Log.cpp
        Log.h
        Makefile
        Member.cpp
        Member.h
        MP1Node.cpp
        MP1Node.h
        Params.cpp
        Params.h
        Queue.h
        stdincludes.h)

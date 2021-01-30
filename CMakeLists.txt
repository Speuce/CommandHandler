cmake_minimum_required(VERSION 3.15)
project(CommandHandler C)

set(CMAKE_C_STANDARD 99)

add_executable(CommandHandler FreeRTOSConfig.h
        task.h queue.h queue.c portable.h can.h main.c Command.h)
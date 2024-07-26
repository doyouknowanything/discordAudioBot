cmake_minimum_required (VERSION 3.16)

set(CMAKE_CXX_STANDARD          17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_RULE_MESSAGES                  OFF)
set_property(GLOBAL PROPERTY USE_FOLDERS ON)

project(DiscordAudioBot)

add_subdirectory(subrepos)
add_subdirectory(src)
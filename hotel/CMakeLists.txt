cmake_minimum_required(VERSION 4.3)
project(hotel)

set(CMAKE_CXX_STANDARD 20)

add_executable(hotel main.cpp
        src/pokoje/Pokoj.cpp
        src/pokoje/Pokoj.h
        src/pokoje/PokojJednoosobowy.cpp
        src/pokoje/PokojJednoosobowy.h
        src/pokoje/PokojDwuosobowy.cpp
        src/pokoje/PokojDwuosobowy.h
        src/pokoje/PokojRodzinny.cpp
        src/pokoje/PokojRodzinny.h
        src/pokoje/PokojRodzinny.h)

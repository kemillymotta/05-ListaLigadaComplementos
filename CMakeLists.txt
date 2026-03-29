cmake_minimum_required(VERSION 3.5)
project(05_ListaLigadaComplementos)

set(CMAKE_CXX_STANDARD 14)

add_executable(ListaLigada
        ListaLigada/ListaLigada/ListaLigada.cpp)

add_executable(ListaLigadaOrdenada
        ListaLigada/ListaLigadaOrdenada/ListaLigadaOrdenada.cpp)
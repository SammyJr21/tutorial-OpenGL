# Definir a versão mínima do CMake
cmake_minimum_required(VERSION 3.10)

# Definir nome do projeto, versão e linguagens suportadas
project(Tutorial-OpenGL VERSION 1.0 LANGUAGES C CXX)

# Definir nome do executável e o(s) arquivo(s) fonte
add_executable(${PROJECT_NAME} main.cpp) 
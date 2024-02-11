project(ZeroSim DESCRIPTION "Simulador 3D" LANGUAGES CXX)
cmake_minimum_required(VERSION 3.28.3)


set(SRC_DIR ${PROJECT_SOURCE_DIR}/src)
set(INC_DIR ${PROJECT_SOURCE_DIR}/inc)

add_executable( ${PROJECT_NAME}
${SRC_DIR}/Main.cpp)

target_include_directories( ${PROJECT_NAME}
PUBLIC
${INC_DIR})

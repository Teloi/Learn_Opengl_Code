cmake_minimum_required(VERSION 3.25)
project(LearnOpengl)

set(CMAKE_CXX_STANDARD 17)

# Configuration
set(LEARN_OPENGL_ROOT ${CMAKE_CURRENT_LIST_DIR})
set(LEARN_OPENGL_THIRD_PARTY ${LEARN_OPENGL_ROOT}/3rd_party)
set(LEARN_OPENGL_INCLUDE_DIR ${LEARN_OPENGL_ROOT})
set(LEARN_OPENGL_INCLUDE_DIR_2 ${LEARN_OPENGL_ROOT}/include)

add_subdirectory(3rd_party)
add_subdirectory(tutorials)
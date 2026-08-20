cmake_minimum_required(VERSION 3.28)

project(CPP_Numerics
  VERSION 0.1.0
  LANGUAGES CXX
)

enable_testing()

add_library(numerics INTERFACE)
target_compile_features(numerics INTERFACE cxx_std_23)

add_subdirectory(tests)
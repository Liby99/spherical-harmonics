cmake_minimum_required(VERSION 3.10)
project(sh)

include_directories(${EIGEN3_INCLUDE})

add_library(sh OBJECT
  sh/image.h
  sh/default_image.h sh/default_image.cc
  sh/spherical_harmonics.h sh/spherical_harmonics.cc
)
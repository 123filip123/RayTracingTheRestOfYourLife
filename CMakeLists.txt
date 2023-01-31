cmake_minimum_required(VERSION 3.21)
project(RayTracingInOneWeekend)

set(CMAKE_CXX_STANDARD 14)

add_executable(RayTracingInOneWeekend main.cpp vec3.h color.h ray.h hittable.h sphere.h hittable_list.h rtweekend.h camera.h material.h)

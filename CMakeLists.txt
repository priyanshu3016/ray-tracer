cmake_minimum_required(VERSION 3.12)
project(raytracer CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(raytracer
    main.cpp
    camera.h
    color.h
    hittable.h
    hittable_list.h
    ray.h
    sphere.h
    vec3.h
)

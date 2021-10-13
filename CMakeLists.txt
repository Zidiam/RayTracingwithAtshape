cmake_minimum_required(VERSION 3.20)
project(RayTracing)

set(CMAKE_CXX_STANDARD 14)

add_executable(RayTracing main.cpp color.h vec3.h ray.h hittable.h sphere.h hittable_list.h rtweekend.h camera.h material.h moving_sphere.h aabb.h bvh.h texture.h perlin.h rtw_stb_image.h aarect.h box.h constant_medium.h lightbox.h tshape.h)

cmake_minimum_required(VERSION 2.8.9)
project (raytracer)
add_executable(raytracer raytracer.cpp)
set_target_properties(raytracer PROPERTIES COMPILE_FLAGS "-save-temps -masm=intel -fverbose-asm -g")

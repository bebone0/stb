cmake_minimum_required(VERSION 3.21)
project(stb)

add_library(stb_image STATIC stb_image.c)
add_library(stb_perlin STATIC stb_perlin.c)
add_library(stb_image_write STATIC stb_image_write.c)
add_library(stb_truetype STATIC stb_truetype.c)

cmake_minimum_required(VERSION 3.16)
project(my_grid_map)

add_subdirectory(grid_map_core)
add_subdirectory(grid_map_sdf)
target_link_libraries(grid_map_sdf grid_map_core)

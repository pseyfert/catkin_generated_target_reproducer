cmake_minimum_required(VERSION 3.5)
project(pkg_c)

find_package(catkin_simple REQUIRED)
catkin_simple(ALL_DEPS_REQUIRED)

cs_add_library(${PROJECT_NAME} src/empty.cc)

cs_install()
cs_export()

cmake_minimum_required(VERSION 3.5)
project(base_msgs)

find_package(catkin_simple REQUIRED)
catkin_simple(ALL_DEPS_REQUIRED)

cs_install()
cs_export()

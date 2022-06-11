cmake_minimum_required(VERSION "3.16.3")
project ("gstcam")
set(CMAKE_CXX_STANDARD 11)
find_package(PkgConfig REQUIRED)
pkg_check_modules(GSTREAMER REQUIRED gstreamer-1.0)
add_subdirectory(src)


PROJECT( artoolkit_utils_proj )
cmake_minimum_required(VERSION 2.6)
# Debug, Release, RelWithDebInfo and MinSizeRe
set(CMAKE_BUILD_TYPE RelWithDebInfo)
SET(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra") # add extra warnings

FIND_PACKAGE(OpenCV REQUIRED)
FIND_PACKAGE(Boost REQUIRED COMPONENTS system)
ADD_SUBDIRECTORY(src)

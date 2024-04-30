cmake_minimum_required(VERSION 3.20)

project("CubicSpline" CXX)

#set(CMAKE_CXX_STANDARD 23)

set(PROJECT_HEADERS
    src/spline.h
)

# install(DIRECTORY src DESTINATION include/CubicSpline)
INSTALL(FILES ${PROJECT_HEADERS} DESTINATION include/CubicSpline)
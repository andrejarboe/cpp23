cmake_minimum_required(VERSION 3.15...4.2)
project(buildProcess LANGUAGES C CXX)

option( BUILD_SHARED_LIBS "Build using shared libraries." OFF )
option(CPPRAST_BUILD_SAMPLES "Build samples." ON)

set(CPPRAST_VERSION_MAJOR 0)
set(CPPRAST_VERSION_MINOR 0)
set(CPPRAST_VERSION_PATCH 1)
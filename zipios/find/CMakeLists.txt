cmake_minimum_required(VERSION 3.12 FATAL_ERROR)

project(samples)

find_package(ZipIos REQUIRED)

if(${ZIPIOSCC_FOUND})
message(STATUS "ZIPIOSCC_FOUND: true")
else()
message(STATUS "ZIPIOSCC_FOUND: false")
endif()
message(STATUS "ZIPIOSCC_INCLUDE_DIR: ${ZIPIOSCC_INCLUDE_DIR}")
message(STATUS "ZIPIOSCC_LIBRARY: ${ZIPIOSCC_LIBRARY}")
message(STATUS "ZIPIOSCC_DEFINITIONS: ${ZIPIOSCC_DEFINITIONS}")

# OUTPUT:
#-- ZIPIOSCC_FOUND: false
#-- ZIPIOSCC_INCLUDE_DIR: /usr/include
#-- ZIPIOSCC_LIBRARY: /usr/lib/libzipios.so
#-- ZIPIOSCC_DEFINITIONS: 



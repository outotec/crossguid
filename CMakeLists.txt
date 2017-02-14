
#
#
#  CMakeLists
#
#

SET( CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} -DGUID_LIBUUID" )

SET(CROSSGUID_SOURCES    
    guid.cpp
)


# Add library crossguid
# ---------------------------

add_library(crossguid ${CROSSGUID_SOURCES})


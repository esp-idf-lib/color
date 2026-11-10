list(APPEND CMAKE_MODULE_PATH ${CMAKE_CURRENT_LIST_DIR}/eil-cmake-utils/cmake)

idf_component_register(
    SRCS color.c
    INCLUDE_DIRS .
    REQUIRES lib8tion
)

include(eil_ci)

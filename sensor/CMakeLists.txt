# CMakeLists.txt at root
set(COMPONENT_SRCS
    "include/sensor.c"
)

set(COMPONENT_ADD_INCLUDEDIRS
    "include"
)

# Register all components in this directory
idf_component_register(
    SRCS ${COMPONENT_SRCS}
    INCLUDE_DIRS ${COMPONENT_ADD_INCLUDEDIRS}
)
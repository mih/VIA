PROJECT(vskel2d)

ADD_EXECUTABLE(vskel2d vskel2d.c)
TARGET_LINK_LIBRARIES(vskel2d via)

INSTALL(TARGETS vskel2d
        RUNTIME DESTINATION ${VIA_INSTALL_BIN_DIR}
        COMPONENT RuntimeLibraries)

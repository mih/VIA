PROJECT(VCROP)

ADD_EXECUTABLE(vcrop vcrop.c)
TARGET_LINK_LIBRARIES(vcrop via)

INSTALL(TARGETS vcrop
        RUNTIME DESTINATION ${VIA_INSTALL_BIN_DIR}
        COMPONENT RuntimeLibraries)

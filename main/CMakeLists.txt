# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES "bluepad32" "btstack")
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS "main.c")
set(COMPONENT_ADD_INCLUDEDIRS "")

register_component(

    REQUIRES "${COMPONENT_REQUIRES}")

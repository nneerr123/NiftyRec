
FILE(GLOB M_FILES "*.m")
INSTALL(FILES ${M_FILES} DESTINATION ${MEX_INSTALL_DIR_NIFTYREC})
FILE(GLOB MAT_FILES "*.mat")
INSTALL(FILES ${MAT_FILES} DESTINATION ${MEX_INSTALL_DIR_NIFTYREC})

SUBDIRS(third_party)


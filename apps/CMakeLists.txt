add_subdirectory(yimage)
add_subdirectory(ytrace)
add_subdirectory(yshape)

add_subdirectory(yscenetrace)
add_subdirectory(ysceneproc)
add_subdirectory(yimageproc)
add_subdirectory(yshapeproc)
add_subdirectory(ymeshproc)
add_subdirectory(yheightfieldproc)
add_subdirectory(ycityproc)

if(YOCTO_OPENGL)
add_subdirectory(ysceneview)
add_subdirectory(ysceneviews)
add_subdirectory(ysceneitrace)
add_subdirectory(ysceneitraces)
add_subdirectory(yimageview)
add_subdirectory(yimageviews)
add_subdirectory(yshapeview)
add_subdirectory(ysculpting)
endif(YOCTO_OPENGL)

if(YOCTO_DENOISE)
add_subdirectory(yimagedenoise)
endif(YOCTO_DENOISE)

add_subdirectory(ymeshtest)

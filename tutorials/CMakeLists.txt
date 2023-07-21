function(add_example example files dependencies)
    add_executable(${example} ${files})
    set_target_properties(${example} PROPERTIES FOLDER "tutorials")
    target_include_directories(${example} PRIVATE ${LEARN_OPENGL_INCLUDE_DIR})
    target_include_directories(${example} PRIVATE ${LEARN_OPENGL_INCLUDE_DIR_2})
    target_link_libraries(${example} PRIVATE ${dependencies})
endfunction()

# Demos
add_subdirectory(01_Hello_Opengl)
add_subdirectory(02_First_Window)
add_subdirectory(03_Hello_Triangle)

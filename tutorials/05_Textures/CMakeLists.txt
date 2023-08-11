get_filename_component(example ${CMAKE_CURRENT_SOURCE_DIR} NAME)
set(dependencies 3rd_glfw)

set(${example}_files
        shader.h
        stb_image.h
        main.cpp
        glad.c
        )

add_example(${example} "${${example}_files}" "${dependencies}")

project(stb LANGUAGES C)

add_library(stb_image STATIC stb_image.h)
set_target_properties(stb_image PROPERTIES LINKER_LANGUAGE C)
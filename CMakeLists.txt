project(stb LANGUAGES C)

add_library(stb STATIC stb.cpp stb_image.h stb_rect_pack.h stb_textedit.h stb_truetype.h stb_sprintf.h)
set_target_properties(stb PROPERTIES LINKER_LANGUAGE C)

target_include_directories(stb PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
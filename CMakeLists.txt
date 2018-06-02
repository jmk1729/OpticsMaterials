project(lib_OpticsMaterials_project)

include_directories ("${PROJECT_SOURCE_DIR}/src")
include_directories ("${PROJECT_SOURCE_DIR}/..")
add_library(OpticsMaterials SHARED OpticsMaterials.c)

install(TARGETS OpticsMaterials DESTINATION lib)
install(FILES OpticsMaterials.h DESTINATION include)


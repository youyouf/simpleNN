
aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR} SRC)

add_library(layer ${SRC})
target_include_directories(layer PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
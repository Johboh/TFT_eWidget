FILE(GLOB_RECURSE lib_sources *.*)

idf_component_register(SRCS ${lib_sources}
                    INCLUDE_DIRS "src/."
                    PRIV_REQUIRES arduino-esp32)
idf_component_register(SRCS "msgpack-c/src"
	INCLUDE_DIRS "msgpack-c/include")

set(CMAKE_C_FLAGS "-DMSGPACK_ENDIAN_LITTLE_BYTE")
list(APPEND PLUGIN_SOURCES
	${CMAKE_CURRENT_SOURCE_DIR}/array.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/float.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/int.cpp
)

set(PLUGIN_SOURCES "${PLUGIN_SOURCES}" PARENT_SCOPE)

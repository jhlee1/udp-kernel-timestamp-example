file(GLOB_RECURSE SRC_FILES CONFIFURE_DEPENDS
        ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp
        )


add_executable(receiver ${SRC_FILES})




add_subdirectory(appshell)
add_subdirectory(context)
add_subdirectory(cloud)

# Domain
add_subdirectory(domain/notation)
add_subdirectory(domain/importexport)

# Home
add_subdirectory(userscores)
add_subdirectory(extensions)
add_subdirectory(languages)

# Scenes common
add_subdirectory(scenes/common)
add_subdirectory(scenes/playback)

# Notation
add_subdirectory(scenes/notation)
add_subdirectory(scenes/palette)
add_subdirectory(scenes/inspector)
add_subdirectory(scenes/instruments)

if (BUILD_UNIT_TESTS)
    add_subdirectory(scenes/notation/tests)
    add_subdirectory(domain/notation/tests)
    add_subdirectory(userscores/tests)
endif(BUILD_UNIT_TESTS)

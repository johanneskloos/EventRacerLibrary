cmake_minimum_required(VERSION 3.7)
add_subdirectory(src)
INSTALL(DIRECTORY src/ DESTINATION include/EventRacer FILES_MATCHING PATTERN "*.h")

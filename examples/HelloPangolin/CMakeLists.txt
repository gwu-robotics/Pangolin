# Find Pangolin (https://github.com/stevenlovegrove/Pangolin)
include_directories(${PANGOLIN_INCLUDE_DIRS})

add_executable(HelloPangolin main.cpp)
target_link_libraries(HelloPangolin ${PANGOLIN_LIBRARIES})

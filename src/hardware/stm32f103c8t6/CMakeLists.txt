SET(CFLAGS "${CFLAGS} -mcpu=cortex-m3")
SET(CXXFLAGS "${CXXFLAGS} -mcpu=cortex-m3")
SET(CMAKE_C_FLAGS   "${CMAKE_C_FLAGS} -mcpu=cortex-m3")
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mcpu=cortex-m3")

add_subdirectory(targets/TBMax-stm32f103)

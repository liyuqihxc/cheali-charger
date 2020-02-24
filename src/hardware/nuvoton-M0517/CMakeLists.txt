SET(CFLAGS "${CFLAGS} -mcpu=cortex-m0")
SET(CXXFLAGS "${CXXFLAGS} -mcpu=cortex-m0")
SET(CMAKE_C_FLAGS   "${CMAKE_C_FLAGS} -mcpu=cortex-m0")
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mcpu=cortex-m0")

#c type menus
#add_subdirectory(targets/AnalogInputsAnalyzer-50W)
add_subdirectory(targets/imaxB6-clone)
add_subdirectory(targets/imaxB6-80W)
add_subdirectory(targets/imaxB6-50W-BOA6)

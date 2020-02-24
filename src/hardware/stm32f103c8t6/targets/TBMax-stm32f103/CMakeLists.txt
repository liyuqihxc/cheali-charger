
set(hardware TBMax-stm32f103)

set(SOURCE_FILES
    defaultCalibration.cpp
    HardwareConfig.h
)

CHEALI_CPU(stm32f103c8t6)
CHEALI_GENERIC_CHARGER(50W)

CHEALI_GENERATE_ARM_EXEC()

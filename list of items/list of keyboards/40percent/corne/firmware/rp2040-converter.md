# RP2040 Converter

## 1. Add `halfconf.h`
```
#pragma once

#define HAL_USE_I2C TRUE
#define HAL_USE_PWM TRUE
#define HAL_USE_PAL TRUE

#include_next <halconf.h>
```
## 2. Add `mcuconf.h`
```
#pragma once

#include_next <mcuconf.h>

#undef RP_I2C_USE_I2C1
#define RP_I2C_USE_I2C1 TRUE

#undef RP_PWM_USE_PWM4
#define RP_PWM_USE_PWM4 TRUE

#undef RP_PWM_USE_TIM1
#define RP_PWM_USE_TIM1 TRUE
```



## 3. Modify `Rules.mk` 
```
# RP2040 converter
# MCU name
MCU = RP2040

# Bootloader selection
BOOTLOADER = rp2040

# Ignore some warnings during the build, likely to be fixed before RP2040 PR is merged
ALLOW_WARNINGS = yes

# LTO must be disabled for RP2040 builds
LTO_ENABLE = no

# PIO serial/WS2812 drivers must be used on RP2040
SERIAL_DRIVER = vendor
WS2812_DRIVER = vendor 

# CONVERTER - if you use a listed MCU comment the first line and uncomment the appropiate line
CONVERT_TO = rp2040_ce  
```

## 4. Make file
```qmk compile -kb crkbd -km vialxc```

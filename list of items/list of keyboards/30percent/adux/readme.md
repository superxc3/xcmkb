# A_Dux

Architeuthis dux 30% board is an open source keyboard. Github refer to [Architeuthis dux](https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux).

This giant sotong with 34 keys, two thumb keys and splayed pinky, ring, index fingers with choc spac just amazing to use with. It comes with plateless but the hole's size is just nice that it fits the switch tightly. 

|![WeChat Image_20221125175539](https://user-images.githubusercontent.com/79617315/203954624-e53de1e5-3423-4d38-a19e-5bc5c99f12ef.jpg)|
|:--:|
|A_Dux without bottom case and plate|

## Firmware
:warning:
Under `rules.mk`, there is a session here called `bootloader`. Default was `atmel-dfu` dedicated for Elite-C. Please change it to `caterina` to avoid mcu bricked.  

```
# Bootloader selection (default was elite-c, do not flash it with promicro, promicro literally bricked)
# BOOTLOADER 	= atmel-dfu # This is for Elite-C
BOOTLOADER 		= caterina	# This is for Promicro
```

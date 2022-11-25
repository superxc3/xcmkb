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

## Notes
:triangular_flag_on_post: Only workable with TRRS cable (4 poles aux cable with 3 lines)

:triangular_flag_on_post: Proved to support MBK and CFX keycaps. Default Kailh blank might interfere. 

:triangular_flag_on_post: No physical reset button designed on the PCB, reset by remap RESET in VIA. 

|![reset](https://user-images.githubusercontent.com/79617315/203957633-1c76beb6-51eb-4acb-ad08-e2a197d9ed7d.jpg)|
|:--:|
|Our board is soldered with new MCU with dedicated reset button, you can press this button twice to reset in QMK Toolbox. However, left side is flipped, you have to use something long and narrow to access it|

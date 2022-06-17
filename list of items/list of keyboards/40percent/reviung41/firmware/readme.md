# Reviung41 QMK Firmware

Sofle is powered by QMK-firmware (Firmware has been merged and can be found on the QMK master). It is officially supported by VIA and can be detected in VIA.

## Rev 2022-2 (2022-06-17)
Features as follow:-
- VIA and VIAL enabled
- 7 layers (0123456)
- 1000hz polling rate for gaming purpose
- Mousekey enabled
- RGB lighting limited to breathing, rainbow swirl, static gradient only
- QMK setting enabled in VIAL (tapping term, osm etc can be configured through vial)
- Hex file ![here](https://drive.google.com/file/d/1VmdizF7vqNpGr--XcyHPtwOJQ__5qCoA/view?usp=sharing)
![image](https://user-images.githubusercontent.com/79617315/174203625-f9460959-7fc5-43fc-aae0-adfd2c6f3eb6.png)




## Rev 2022-1 (2022-02-11)
Board after this date is flashed with this firmware. You can check which firmware being flashed in your Invoice.

Features as follow:-
- VIA (auto-detected)
- 6 layers (012345)
- 1000hz polling rate for gaming purpose

## VIA
- [x] Mousekey
- [x] Extrakey (media control)
- [x] NKRO

### RGB LIGHTING
- [x] Enabled
- [ ] #define RGBLIGHT_ANIMATIONS (all enabled)

The firmware size is approaching the maximum - 27874/28672 (97%, 798 bytes free)

## Rev 2022-1A (2022-02-11)
**Special request by buyer who wishes to disable the front led due to glare from transparent switch plate*

All features same as Rev 2022-1 above except front led being disabled.
  #define RGBLED_NUM 10 under config.h




Kindly contact XCMKB for firmware.

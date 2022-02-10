# Sofle QMK Firmware

Sofle is powered by QMK-firmware (Firmware has been merged and can be found on the QMK master).

## Rev 2022-1 (2022-02-10)
**Some boards before this date and all boards after this date is flashed with this firmware*

Features as follow:-
- Left and right can be master
- VIA (auto-detected, rotary encoders cannot be programmed here)
- VIAL (auto-detected)
- 6 Layers (layer 012345)
- added #define SPLIT_USB_DETECT under config.h due to batch of promicro issue

### OLED
#### Master OLED
- [x] Layers
- [x] Capslock
- [ ] WPM 

#### Slave OLED
- [x] LOGO (QMK default logo)

![image](https://user-images.githubusercontent.com/79617315/153364844-cf18d8dc-ca95-4d0b-b41e-049613fa2b2e.png)
### VIA
- [x] Mousekey 
- [x] Extrakey (to control media)
- [x] NKRO

![image](https://user-images.githubusercontent.com/79617315/153364700-e089107d-1eaf-4cef-8847-e94f41467d8e.png)

### VIAL
- [x] Programmable rotary encoders (clockwise/anti-clockwise)
- [ ] QMK Settings
- [ ] Combo Enable
- [ ] Tap Dance

### RGB LIGHTING (manual led strip)
- [ ] Enabled
- [ ] RGB matrix 
- [ ] RGBLIGHT_EFFECT_RAINBOW_SWIRL

Kindly contact XCMKB for firmware.

# Sofle ZMK Firmware
Supported by ZMK. Do refer ![here](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20zmk) for setting up ZMK assembled by us.

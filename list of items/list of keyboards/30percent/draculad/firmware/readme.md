# Draculad QMK Firmware

Draculad is powered by QMK-firmware (Firmware has been merged and can be found on the QMK master). 
The official firmware does not support VIA or VIAL.

## Rev 1 (2022-02-10)
The first revision done by XCMKB. Features as follow:-
- Left and right can be master
- VIA (manual load json)
- VIAL (auto-detected)
- 6 Layers (layer 012345)
- Pimoroni on left 

*pimoroni can be on right slave, firmware needs to be configured to rotate the TRACKBALL INVERT under config.h. You may check qmk doc for detailed rotation*

### OLED
![image](https://user-images.githubusercontent.com/79617315/153377559-3bde97cc-35d4-4c95-a33e-b82d97092ae9.png)

#### Master OLED
- [x] Layers
- [x] Capslock
- [ ] WPM (enabled by default; removed to squeeze in vial)

#### Slave OLED
- [x] LOGO (Default Draculad Logo)

### VIA
- [ ] Mousekey (however enabled in via json and usable)

### VIAL
- [x] Programmable rotary encoders (clockwise/anti-clockwise)
- [ ] QMK Settings
- [ ] Combo Enable
- [x] Tap Dance

### RGB LIGHTING
- [x] Enabled
- [ ] RGB matrix 
- [x] RGBLIGHT_EFFECT_RAINBOW_SWIRL

Kindly contact XCMKB for firmware.

# Draculad ZMK Firmware
Not officially listed or written by author.

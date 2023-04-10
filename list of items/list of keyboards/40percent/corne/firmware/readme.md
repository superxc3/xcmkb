# Corne Firmware

1. With vial enabled, qmk settings, rgb (limit to 3) and oled enabled, mousekey disabled: firmware oversize (3372 bytes over)
2. Refer setting above, oled disabled, firmware 93%. 
3. Refer setting 1, oled disabled, mousekey enabled, rgb limit to 2, firmware 99%, 192 bytes free.
4. The board you bought is already pre-flashed, we do not recommend you to flash it unless you are aware what you are doing. 
5. Refer [Flashing Hex](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md) for steps to flash hex. 
6. All corne firmware rev download from [here](https://share.multcloud.link/share/c831cb3e-590b-4b11-b883-bfa68798e0cf).

## ZMK Wireless 
Please check [zmk-config-crkbd](https://github.com/superxc3/zmk-config-crkbd).


## Standard Firmware (2023.04.05)
1. For RGB, the board is flashed with Rev 2023-3u.
2. For non-rgb, the board is flashed with Rev 2023-3.

## Rev 2023-3u
- RGB enabled, qmk settings disabled
- the rest similar to Rev 2023-3

## Rev 2023-3
- fix board does not wake up after restart
- RGB disabled, mousekey enabled, qmk settings enabled
- 6 layers


## Rev 2023-2 (2023-01-08)
Built based on rev1. Disable rgb, enable qmk settings and mousekey. The firmware size is approaching the maximum - 27928/28672 (97%, 744 bytes free)
### Features
- a total of 8 layers (Layer 0 - 7)
- oled yes
- vial and via yes
- qmk settings yes, combo, tap dance no
- mousekey yes
- rgb disabled
- tapping term 200
- ignore mod tap interrupt
- split usb detect 
- usb polling 1000

## Rev 2023-1 (2023-01-06)
Suitable for user who looking for vial-enabled firmware. This is created to allow keyboard to be mapped with vial as recent via firmware is incompatible in vial. 
- enable vial 
- due to increasing size, mousekey is disabled

### Features
- a total of 8 layers (Layer 0 - 7)
- oled yes
- vial and via yes
- qmk settings, combo, tap dance no
- mousekey no
- rgb enabled with Rainbow mood, Static gradient, Rainbow swirl, Breathing only
- tapping term 200
- ignore mod tap interrupt
- split usb detect 
- usb polling 1000


## Rev 2022-3 (2022-12-21)
- modified based on Rev 2
- layers up to 8 (0-7)
- tapping term changes to 200
- add mousekey modification in config.h based on request
- the rest are same
- vial is not enabled but you can remap in ~~vial~~/via. vial will read it as via config.
- rgb underglow lighting effect cant be edit in vial, only in via. 

`Recent VIA firmware is completely incompatible with Vial. The "unsupported protocol" message means you've got recent VIA firmware flashed, which means you will need to use the VIA website until you finish and flash the Vial keymap.`

## Rev 2022-2 (2022-12-15)
- split usb detect
- layers up to 7
- tapping term 180
- ignore mod tap interrupt
- usb pooling interval ms1
- qmk keys per scan 12
- rgb: rainbow mood, static gradient, rainbow swirl, breathing
- enabled mousekey
- enabled oled


## Rev 2022-1 (2022-06-19)
- split usb detect
- no rgb
- oled enabled
- IGNORE_MOD_TAP_INTERRUPT
- tapping term 230
- layers add up to 7
- rgb sleep enable
- QMK settings in vial
- mousekey disabled

## Rev 2021-1 (2021-11-22)
- Layers added up to 6
- Media key enabled
- Mousekey enabled
- RGB lighting all enabled


## Rev 2022-1 (2022-03-10)
Added VIAL support for certain features:
- Layers added up to 8
- Added VIAL support by enabling QMK settings and Tap dance
- Combo is still disabled due to size limit
- Mousekey is disabled to accommodate for QMK settings and Tap dance in VIAL
- Oled is disabled to accommodate for QMK settings and Tap dance in VIAL

RGB lighting
- [x] RGBLIGHT_EFFECT_BREATHING
- [x] RGBLIGHT_EFFECT_RAINBOW_MOOD
- [x] RGBLIGHT_EFFECT_RAINBOW_SWIRL
- [ ] RGBLIGHT_EFFECT_SNAKE
- [ ] RGBLIGHT_EFFECT_KNIGHT
- [ ] RGBLIGHT_EFFECT_CHRISTMAS
- [x] RGBLIGHT_EFFECT_STATIC_GRADIENT
- [x] RGBLIGHT_EFFECT_RGB_TEST

|![image](https://user-images.githubusercontent.com/79617315/157654494-7f1aa6e9-c5b2-4e1c-9076-ff4fa77e263e.png)|
|:--:|
| QMK Settings in VIAL |

| ![image](https://user-images.githubusercontent.com/79617315/157654570-f283d9f6-7724-46c9-acfd-0cfaa9279a21.png)|
|:--:|
| Tap Dance in VIAL |

## Rev 2022-0 
- Layers 4 (0,1,2,3)
- RGB lighting effect all
- Mousekey disabled






# Corne Firmware

1. With vial enabled, qmk settings, rgb (limit to 3) and oled enabled, mousekey disabled: firmware oversize (3372 bytes over)
2. Refer setting above, oled disabled, firmware 93%. 
3. Refer setting 1, oled disabled, mousekey enabled, rgb limit to 2, firmware 99%, 192 bytes free.

## Rev 2022-3 (2022-12-21)
- modified based on Rev 2
- layers up to 8 (0-7)
- tapping term changes to 200
- add mousekey modification in config.h based on request
- the rest are same
- vial is not enabled but you can remap in vial/via. vial will read it as via config.


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






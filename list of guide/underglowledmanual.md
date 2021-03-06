# Underglow LED strip 

| ![image](https://user-images.githubusercontent.com/79617315/161470632-a49aaec8-75f1-4c8b-bc0f-72466521a6dc.png) |
|:--:|
| Raw material : LED strip with 7 rgb leds each side + wire for connection |



| ![image](https://user-images.githubusercontent.com/79617315/161470727-b35ee321-62b7-42b4-bb41-6c63b5441fc7.png) |
|:--:|
| Soldered and prepared by XCMKB |

## Preparation / manual

| ![image](https://user-images.githubusercontent.com/79617315/161470879-eb73b59c-c436-49e0-b301-b4ce85db73ab.png) |
|:--:|
| Step 1: fill the solder point with solder wire on the bottom of PCB (note that this is the front of pcb) |


|![image](https://user-images.githubusercontent.com/79617315/161470784-17db07f5-9522-4d60-87c3-30dffbf60d77.png)|
|:--:|
| Step 2: Left slave: GND connects to G; Di connects to middle solder point|

|![image](https://user-images.githubusercontent.com/79617315/161471003-af95582e-bb10-4473-8fd5-73e5690b0637.png)|
|:--:|
| Step 3: Right slave: VCC connects to +5v, LED to Di, last one to G |


|![e](https://user-images.githubusercontent.com/79617315/161472226-e7951249-2772-4feb-98be-31d9a95adc5b.jpg)|
|:--:|
| Remove the sticker and paste it at the bottom of pcb. REMEMBER! Avoid the exposed wire contact/touching any silver color pad |

## Firmware
If your board is flashed with ## Rev 2022-1 (2022-02-10); you can only choose single RGB lighting in VIA. If you wish to accommodate for more RGB lighting effect, you will need to flash with new firmware ## Rev 2022-5 RGB Underglow for extra RGB lighting effect. Note that we are unable to include all RGB lighting effect in VIA as we have enabled programmable rotary encoder in VIAL; and at the same time mousekey is disabled, meaning scroll wheel etc. will not registered even remapped in VIA. 

Hence, only certain RGB lighting effect is workable in VIA for ## Rev 2022-5 RGB Underglow
- [x] RGBLIGHT_EFFECT_RAINBOW_SWIRL
- [x] RGBLIGHT_EFFECT_RAINBOW_MOOD
- [x] RGBLIGHT_EFFECT_BREATHING
- [x] RGBLIGHT_EFFECT_STATIC_GRADIENT

Manual and tutorial on flashing new firmware refer [here](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20v1%20&%20v2%20mx/firmware/readme.md#rev-2022-5-rgb-underglow).



# Sofle QMK Firmware

Sofle is powered by QMK-firmware (Firmware has been merged and can be found on the QMK master). The firmware here are highly customised and modified by us, they are used to flash your boards before we ship to you. Hence, list of firmwares here are totally different from the default QMK VIA firmware found at the [official repo](https://qmk.fm/keyboards/). 

# Standard Firmware Flashed for Sofle V2 (2023.06.22)
1. Standard wired firmware flashed after this date: `Rev 2023-4-3 Oled bug`.
2. For Sofle without underglow, flashed with: `xcmkb_sofle_vial-ud.hex`.
3. For Sofle with underglow RGB strip and RGB per key, flashed with: `xcmkb_sofle_vial_udrgb.hex`.
4. The board you bought is already pre-flashed, we do not recommend you to flash it unless you are aware what you are doing or advised by us.
5. Refer [Flashing Hex](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md) for steps to flash hex. 
5. Firmware download from [here](https://drive.google.com/drive/u/0/folders/19jDXbsa5eFDwiKjC7scXAqYjvtuJ-qrr).

## Rev 2023-4-3 Oled bug (xcmkb_sofle_vial-ud or xcmkb_sofle_vial-udrgb)
- Date: 2023.04.28
- Similar to previous update, fix bug on MO(2) and above misaligned. 
- Sofle RGB/Underglow: vial-udrgb
- Sofle without RGB/Underglow: vial-ud

## Rev 2023-4-4 no oled, no rgb (xcmkb_sofle_vial-ud-nooled)
- Date: 2023.07.07
- Built based on xcmkb_sofle_vial-ud
- No oled, no rgb
- Mousekey enable
- QMK Settings, Tap dance enable
* The firmware size is approaching the maximum - 28130/28672 (98%, 542 bytes free)

## Rev 2023-4-1 Sofle usb alt
- without RGB lighting and enable mousekey
- unable to squeeze in qmk settings (1244 bytes over)
- the rest similar to Rev 2023-4

## Rev 2023-4 Sofle RGB usb detect
- fix the board does not wake after restart
- the rest similar to Rev 2023-3 All kinds of Sofle

## Rev 2023-3 Vial update for all kinds of Sofle (RGB)
Due to QMK Firmware and vial update, new firmware is written to avoid conflict. Do download `xcmkb_sofle_vial-superalttab-left` and right and flash using QMK Toolbox, refer [Tutorial to flash split keyboard](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md). 

This firmware supports all kinds of Sofle including v2 and lp choc with RGB lighting. In order to enable RGB lighting, mousekey is disabled. 

### Features
- Vial enabled
- Total of 6 layers (012345)
- RGB underglow and rgb per key
- RGB lighting effects limited to Rainbow Mood, Rainbow Swirl, and Static Gradient only
- Super alt tab enable to cycle between different windows (check User in Vial)
- QMK settings, combo and tap dance in vial are disabled
- Mousekey disabled
- Permissive hold, ignore mod tap interrupt, tapping force hold are enabled
- USB polling interval ms1
- Split usb detect for some batches of promicro
- vial update for Encoder map enabled


## Rev 2023-2 Animated luna without RGB
Built based on Rev 2023-1, added animated luna due to 10% size available. `Debugging and cannot be released, flicker oled due to animated luna`
### Features
- Vial enabled
- RGB underglow no
- Mousekey yes
- QMK settings, combo, tap dance disabled
- Layer 6 (Layer 0 to 5) 
- Animated luna oled

## Rev 2023-1 Vial update
This is a new update on vial repo. The firmware size is fine - 25930/28672 (90%, 2742 bytes free). QMK settings cannot be enabled. The firmware is too large! 29390/28672 (718 bytes over).

### Features
- Vial enabled
- RGB underglow no
- Mousekey yes
- QMK settings, combo, tap dance disabled
- Layer 6 (Layer 0 to 5)

## Rev 2023-1u Vial update
This is a new update on vial repo with rgb underglow enabled for board with rgb strip, mousekey has to be disabled (720 over). * The firmware size is approaching the maximum - 28374/28672 (98%, 298 bytes free)

### Features
- Vial enabled
- RGB underglow yes, limit to RGB breathing, rainbow mood, rainbow swirl, static gradient only
- Mousekey no
- QMK settings, combo, tap dance disabled
- Layer 6 (Layer 0 to 5)

## Rev 2022-5 RGB Underglow Backup
- A backup of RGB underglow if [Rev 2022-5 RGB Underglow](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20v1%20%26%20v2%20mx/firmware#rev-2022-5-rgb-underglow) is not working.
- This is an old version of RGB underglow hex, the details or features are unknown; but it supports vial and programmable encoder through vial.

Hex file download [here left](https://drive.google.com/file/d/1jKl9Fi0LPyQU0BImzz2hgnSC7xnRrUby/view?usp=sharing); [here right](https://drive.google.com/file/d/1CWC9zTRC3DdU_ad5FRjD7YQFDK1K_ROS/view?usp=sharing)

 Tutorial of flashing hex refer [here](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md)


## Rev 2022-7 Pimoroni trackball (right) 
- Pimoroni trackball on right
- Oled screen must be two: master shows: SOFLE PMRNI; Layer; Lock, Caps, Num, Scr
- VIA only, knobs programmable through VIA.
- Underglow with led strip
- Trackball inverted accordingly in common config
- Ignore mod tap interrupt
- USB polling ms1
- QMK keys per scan 12
- NKRO enable
- RGB Breathing, Rainbow Swirl, and Static Gradient only
- RGB limit val 160
- RGB sleep
- 6 layers
- mo(4) change to precision and trackball color 
- do note that trackball color is not stable
- grave esc space cadet enable
- extrakey yes
- mousekey no

![image](https://user-images.githubusercontent.com/79617315/182025550-35115ca8-1a52-4d86-81e1-1e9b72da503d.png)
Link [here](https://drive.google.com/drive/u/0/folders/1sxq4S5OrDOqtABkj5xniupb6zXo-uXHVxc)

## Rev 2022-5-1 RGB Sleep
- Modified based on Rev 2022-5 RGB underglow
- Turn off LEDs when computer sleeping
- Utilise power draw USB limitations

## Rev 2022-5 RGB Underglow
- Modified based on [Rev 2022-1 (2022-02-10)](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20v1%20%26%20v2%20mx/firmware#rev-2022-1-2022-02-10)
- [ ] Mousekey 
- [x] Extrakey (to control media)
- [x] NKRO
- [ ] Disabled tap dance to accommodate extra rgb lighting effect

### RGB LIGHTING (manual led strip)
- [x] Enabled
- [ ] RGB matrix 
- [x] RGBLIGHT_EFFECT_RAINBOW_SWIRL
- [x] RGBLIGHT_EFFECT_RAINBOW_MOOD
- [x] RGBLIGHT_EFFECT_BREATHING
- [x] RGBLIGHT_EFFECT_STATIC_GRADIENT

 * The firmware size is approaching the maximum - 28510/28672 (99%, 162 bytes free)

 Hex file download [here](https://drive.google.com/drive/u/0/folders/1g7OomsH3gYjbrHQGPnhhqWuzIPQ4A_Np).
 
 Tutorial of flashing hex refer [here](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md)
 


## Rev 2022-4 Pimoroni trackball (left) (2022-04-12)
- A revision from [rev 2022-3](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20v1%20%26%20v2%20mx/firmware#rev-2022-3-pimoroni-trackball-2022-03-20) as trackball moved to left
- Fixed buggy col 0 and row 0; keymap enable in VIA, no more random codes
- Fixed keymap reversed issue
- Fixed rgb led strip (original was rgb per key from keyhive)
- Disable heptic bzzz
- OLED on slave as QMK logo, master as "SOFLE PMRN" and layers
- Total of 6 layers: 012345
-  Link [here](https://drive.google.com/drive/u/0/folders/1w-SaXB190X9ZZumO4TqyWgcI9mFePxybxc)

### RGB LIGHTING (manual led strip)
- [x] Enabled
- [ ] RGB matrix 
- [x] RGBLIGHT_EFFECT_RAINBOW_SWIRL
- [ ] RGBLIGHT_EFFECT_RAINBOW_MOOD
- [x] RGBLIGHT_EFFECT_BREATHING
- [x] RGBLIGHT_EFFECT_STATIC_GRADIENT

## Rev 2022-3 Pimoroni trackball (2022-03-20)
**Pimoroni Trackball version, left and right can be master*
- Inspired by Solartempest
- VIA only, no VIAL. Manual load json
- Programmable knob rotation through VIA
- Left and right can be pimoroni as long as it is hotswap
- OLED on both sides (and must), one side OLED installed might cause OLED not show up properly
- Layer 0 and other as scroll; Layer 4 as precision

|![image](https://user-images.githubusercontent.com/79617315/159146852-50b50896-7e8e-4c4f-9c12-b39d5a747f82.png)|
|:--:|
| VIA only, however programmable knob ||

## Rev 2022-2 no oled (2022-03-04)
**No oled version, reduced spaces are filled with tap dance and qmk settings in vial feature*

This revision are same as Rev 2022-1, except OLED being disabled; and extra features:
### VIAL
- [ ] QMK Settings
- [X] Combo Enable
- [X] Tap Dance

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

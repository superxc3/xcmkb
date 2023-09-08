# Changelog 

## Firmware: Version 2.0 beta
Released on September 8, 2023, `xcmkb_sofleplus_2040_vial-spacexc_rp2040_ce`, [Download](https://drive.google.com/file/d/1GajHL9OGIlprdd9wH9aA6EoxqdFUEF9C/view?usp=drive_link). Thanks to NoZuoNoDie, a fews significant changes have been implemented. The codes are edited accordingly to suit for everyone usage. 

Main changes:
1. Animated OLED: wpm responsive space and animated calcifer
2. Trackball is now light up as Capslock (red), Numlock (turquoise), and Trackball layer indicator (white)
3. Haptic support is now returned, but only works on master. 
4. Bugs and improvements

### Animated OLED
WPM responsive space is designed and created by [admiralalleki](https://www.reddit.com/r/MechanicalKeyboards/comments/y916bk/i_programmed_my_corne_oled_via_qmk_to_show_a/). While animated calcifer inspired from [Semput](https://www.youtube.com/@semputs), wanted to make it long time ago but finally yay!

### Bugs and improvements
1. Fixed User labels show properly
2. A few new attributes added by NZND, hover to know the usage
3. When move your trackball, it goes to last layer automatically. OLED shows "TBALL" and trackball lights up in white color. 

### Known issues
1. Pressing keys on board cannot wake the pc, seems like a known issue for board with pimoroni trackball.

   
## Firmware: Version 1.2AOLED beta
Removed and replaced with better Version 2.0

## Firmware: Version 1.2
Released on August 3, 2023, `xcmkb_sofleplus_2040_vial-ud-p_rp2040_ce-v1.2(left/right)`. Fixed the first RGB led not lit up. 

## Firmware: Version 1.1
Released on August 1, 2023, `xcmkb_sofleplus_2040_vial-ud-p_rp2040_ce(left/right)`. Fixed the main issue of replugging required after a fresh restart and added RGB matrix support. This version is merged with the release of Vial version 0.7 on July 15, 2023. 

### Re-plug in the usb cable is required after PC restarts.
Changed `CONVERT_TO = rp2040_ce` from the old `#CONVERT_TO = promicro_rp2040`, as Splinky differs from Sparkfun's.

### RGB improvement
1. RGB pin redefined. Deprecated RGB data pin from `#define RGB_DI_PIN D3` to `#define WS2812_DI_PIN D3`.
2. Add `#define RGB_DISABLE_WHEN_USB_SUSPENDED` in config.h as RGBLIGHT_SLEEP is not working on none-rgb light.
3. The more colorful RGB Matrix is added. Refer to [RGB matrix effect](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_rgb_matrix.md#rgb-matrix-effects-idrgb-matrix-effects) for list of effects.
4. Some RGB matrix effects work best for rgb per key mode, do explore yourself which suits your needs. For instance, `Rainbow Moving Chevron`, `Cycle All`, or `Hue Breathing` working better on RGB underglow.
   
   ![image](https://github.com/superxc3/xcmkb/assets/79617315/2e9f05f7-674a-4c65-b368-debbbf305d9c)

### Fix keycode in User Tab
Some words could not be read properly. Fixed with a shorter short form, but USER01 which should be read as ABR, can still not be fixed.

![image](https://github.com/superxc3/xcmkb/assets/79617315/a41fed82-5fb4-412b-8767-c34320dde884)

## Firmware: Version 1.0
The very first released rp2040 promicro firmware, `xcmkb_sofleplus_2040_vial-ud-p_promicro_rp2040-left/right-3`.

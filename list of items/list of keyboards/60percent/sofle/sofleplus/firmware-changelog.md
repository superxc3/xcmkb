# Changelog 

## Firmware: Version 1.2AOLED beta
Released on August 15, 2023, `xcmkb_sofleplus_2040_vial-ud-p_rp2040_ce-v1.2AOLED(left/right)`. If you find this [Version 1.2AOLED](https://drive.google.com/drive/u/0/folders/18RLAtqyae9TjMOiLKMwhJUlh-HlSbQ1s) is unstable, please revert to [Version 1.2](https://drive.google.com/drive/u/0/folders/1PH2i1OQQut_ADcWHp_RfRwOdZxHYM62C). 

Main changes: adopted animated pets and layer indicators through RGB light.

### Animated OLED
1. Right as Luna with WPM responsive; capslock triggers barking luna.
2. Left shows typing wpm in digit form

### RGB Layer indicator
1. Add RGB indicator for layer 1 (teal); 2 (purple); 3 (yellow); 4 (blue). The rest are not added, suitable for users who do not want RGB indicator.

### Known issues
1. By touching the keys may not able to wake the computer from sleep if the trackball is already in deep sleep. You need to use mouse to wake your computer.
2. RGB seems unable to sleep after leave idle.
3. Sometimes keyboard is acting weird during fresh restart, re-plugging usb c and leave it idle from 10s then only start using it seems able to fix. Still monitoring.
   
### Future patches
1. To fix known issues listed
2. To add left pet to oled
3. To add rgb for trackball
4. Haptic buzz is disabled due to certain confliction that requires to debug.

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

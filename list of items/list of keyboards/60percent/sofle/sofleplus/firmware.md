# Firmware of Sofle Plus

Sofle is powered by QMK-firmware (Firmware has been merged and can be found on the QMK master). The firmware here are highly customised and modified by us, they are used to flash your boards before we ship to you. Hence, list of firmware here are totally different from the default QMK VIA firmware found at the [official repo](https://qmk.fm/keyboards/). 

Sofle Plus is compatible with any Sofle v2 or v1 firmware, as well as Choc firmware, but not with firmware from Keyhive. It is specifically designed based on the RP2040 ProMicro, incorporating all functions and capabilities in Vial. 

### Features
1. Auto-detected in [Vial software](https://get.vial.today/download/), supports Win, Linux, and Mac. Real-time key remap software without the needs of code compilation. No load json is required. 
2. 10 [Layers](https://get.vial.today/manual/layers.html), maximum fn! You can refer to [Miryoku](https://github.com/manna-harbour/miryoku) for inspiration.
3. 32 [Combos](https://get.vial.today/manual/combos.html), adds custom actions when a certain combination of keys is pressed.
4. 32 [Tap dance](https://get.vial.today/manual/tap-dance.html), taps and hold for different key outputs.
5. 32 Key overrides
6. QMK Settings allows you to configure the fine details of how QMK operates, including tapping term, permissive hold etc. Read more on [QMK Firmware](https://docs.qmk.fm/#/).
7. Mousekey allows you to remap mouse key on keyboard, including left click, right click, scroll etc.
8. RGB Light enabled and including all RGB lighting effects.
9. Pimoroni trackball and haptic bzzz enabled. 
10. Left and right can be master, meaning either side can be used to plug in usb-c. But trackball and bzzz must be on the master.

#### User Tab Explanation
1. `Super ALT↯TAB` is enabled in `User` tab as `ABF` and `ABR/User01`, allowing you to cycle tab through window, especially suitable for knob function.
2. `AMWU` and `AMWD` denotes Alt + Mousewheel allows you to control brush size in Photoshop.
3. `NMR` and `NML` move your window to left or right monitor, if you have two monitors.
4. `SBS` denotes Shift + Backspace to delete whole word.
5. `SCR` hold to scroll pimoroni trackball.
   
# Standard Firmware of Sofle Plus (RP2040)
1. All wired versions of Sofle Plus come pre-flashed with this firmware.
2. The board you purchased comes pre-flashed, except for the build kit. We strongly advise against flashing it unless you are familiar with the process or have been instructed to do so by us.
3. Refer to [Flashing uf2](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/flashingboard.md) tutorial for flashing.
5. On this date `2023.08.01`, we are using **Version 1.1** as standard firmware. List of uf2 downloads from [here](https://drive.google.com/drive/u/0/folders/1vNPOlv2NhzNlO9qoJ0fS3oOtKQtKS7rQ).

## Version 1.1
Released on August 1, 2023, `xcmkb_sofleplus_2040_vial-ud-p_rp2040_ce(left/right)`. Fixed the main issue of replugging required after a fresh restart and added RGB matrix support.

### Bug Fixes & Improvements 
Merged with the release of Vial version 0.7 on July 15, 2023. 

### Re-plug in the usb cable is required after PC restarts.
Changed `CONVERT_TO = rp2040_ce` from the old `#CONVERT_TO = promicro_rp2040`, as Splinky differs from Sparkfun's.

### RGB pin redefined
Deprecated RGB data pin from `#define RGB_DI_PIN D3` to `#define WS2812_DI_PIN D3`.

### Adding RGB Matrix support instead of RGB light only
Since we dont have firmware size limits, we have enabled support for the more colorful RGB Matrix. Add `#define RGB_DISABLE_WHEN_USB_SUSPENDED` in config.h as RGBLIGHT_SLEEP  not working on none-rgb light.
![image](https://github.com/superxc3/xcmkb/assets/79617315/e5dde50f-b90a-4182-a233-69aabb2f04c7)

### Fix keycode in User Tab
Some words could not be read properly. Fixed with a shorter short form, but USER01 which should be read as ABR, can still not be fixed.
![image](https://github.com/superxc3/xcmkb/assets/79617315/a41fed82-5fb4-412b-8767-c34320dde884)

 
# Archives

## Version 1.0
The very first released rp2040 promicro firmware, `xcmkb_sofleplus_2040_vial-ud-p_promicro_rp2040-left/right-3`.


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
8. RGB Matrix is now enabled and including all RGB lighting effects. More colorful, more lively!
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
5. On this date `2023.08.01`, we are using `Version 1.1` as standard firmware. List of uf2 downloads from [here](https://drive.google.com/drive/u/0/folders/1vNPOlv2NhzNlO9qoJ0fS3oOtKQtKS7rQ).
6. Read [Changelog](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/firmware-changelog.md) for firmware version features or improvements.




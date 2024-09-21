# CornePLUS Firmware
All wired version use RP2040 firmware, we stop maintain atmega32u4 promicro.
1. Splinky or similar RP2040 Promicro user, please check [RP2040 Promicro](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/40percent/corne/firmware#rp2040-promicro).
2. ZMK Wireless, please head to [zmk-config-crkbd](https://github.com/superxc3/zmk-config-crkbd).

# RP2040 Promicro

## [v2.02b](https://drive.google.com/file/d/1D2sjhvIMXPaJuxE4MZU9Rsl5Hdgqv-j4/view?usp=sharing)
- Aligned with SoflePLUS firmware version, hence rename to v2.02b
- Display shows DPI due to Trackpad, corrected both sides display to show status only, no more wpm rocket.
- Added trackpad 43, corrected orientation.
- Left and right can be master.

## [v0.5](https://drive.google.com/drive/folders/12LtxLUCY4crnO1c1aplqwu-pg4pVLYCl)
- Adds layout option for 42/36 keys corne, flat wheel encoders yes or nil
  
## v0.4
![2024-01-12 11-52-50](https://github.com/superxc3/vial-qmk/assets/79617315/51ffac07-195d-454f-aedd-1a3236d725f2)

## Features
1. Auto-detected in [Vial software](https://get.vial.today/download/), supports Win, Linux, and Mac. Real-time key remap software without the needs of code compilation. No load json is required. 
2. 10 [Layers](https://get.vial.today/manual/layers.html), maximum fn! You can refer to [Miryoku](https://github.com/manna-harbour/miryoku) for inspiration.
3. 32 [Combos](https://get.vial.today/manual/combos.html), adds custom actions when a certain combination of keys is pressed.
4. 32 [Tap dance](https://get.vial.today/manual/tap-dance.html), taps and hold for different key outputs.
5. 32 Key overrides
6. QMK Settings allows you to configure the fine details of how QMK operates, including tapping term, permissive hold etc. Read more on [QMK Firmware](https://docs.qmk.fm/#/).
7. Mousekey allows you to remap mouse key on keyboard, including left click, right click, scroll etc.
8. RGB Matrix is now enabled and including all RGB lighting effects. More colorful, more lively!
9. Left and right can be master, meaning either side can be used to plug in usb-c.

## Source code
Our [source codes](https://github.com/superxc3/vial-qmk/blob/corneplus/keyboards/crkbd/readme.md) will be provided to our clients and should not be disclosed to the public. They are restricted for personal use only. Please note that flashing the board is done at your own risk, and we are not responsible for any board failure resulting from flashing.







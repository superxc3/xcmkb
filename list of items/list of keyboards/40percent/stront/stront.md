# STRONT
Stront is designed by [zzeneg](https://github.com/zzeneg/stront). This is a split keyboard with 38 keys, LCD display and trackpad (Azoteq or Cirque).

|![afcede863b9432fdc34d01f6b55b028](https://github.com/superxc3/xcmkb/assets/79617315/2034e919-e26a-41b7-a505-2e366c0933d9)|
|:--:|
| Stront MX with frosted transparent resin, cirque trackpad, dual knobs, Buger XDA TH01 keycap |

## Features
- MX, KS-33 or Choc switches hotswap (choose one only)
- wired split with USB-C or TRRS interconnection
- 38 keys
- roller for gateron low profile and choc, knob for mx
- LCD display (1.69" 240x280 by default)
- Azoteq/Cirque trackpad support
- 2-key pinky columns
- 3D printed cases (frosted transparent resin / clear transparent resin)
- modifications are subject to change, please confirm with seller before checkout

### Pointing device features
1. Cirque trackpad: tap for left click, outer circular gesture to scroll up or down
2. Azoteq: tap for left click, two fingers tap for right click, two fingers moving up and down for scrolling, tap once and hold to drag
*Other features are not available unless mentioned above.*

### HID LCD features
1. Please refer to [qmk-hid-host](https://github.com/zzeneg/qmk-hid-host).
2. This is compatible for Win and Linux only, no Mac.
   
## Attention
1. The USB-C port in the middle is used to connect both splits only; do not connect it to your PC, or your keyboard may become unusable.
2. Connect one side to your PC only; do not use both sides simultaneously. The extra USB-C port cannot be used as a pendrive, etc.
3. Always connect the USB-C cable between the splits first, and then connect the other end to your PC. This practice is recommended.
4. We are not responsible if you brick your boards due to rough connections. Always ask for assistance if you are unsure; we are happy to help.

## Keyremap
|![image](https://github.com/superxc3/xcmkb/assets/79617315/2edcd675-2aec-4c48-b045-7f3acab55c26)|
|:--:|
|Ported with vial by Author|
1. Download [Vial](https://get.vial.today/). Vial is a feature-rich open-source cross-platform (Windows, Linux and Mac) GUI and a QMK fork for configuring your keyboard in real time.
2. You also can use [Web Vial](https://vial.rocks/) to remap the key if you are not allowed to install software to your device. Alternatively, the board is using on-board memory, so what you have remapped will be brought over to another device. Web Vial might not work for Safari and Firefox. 


## Firmware
This is an open-source board by zzeneg. We have enhanced the firmware based on our expertise and user feedback. Our code remains confidential, even for our clients. Feel free to explore the original code from the author by visiting this [link](https://github.com/zzeneg/stront#firmware). Happy coding!

### 20240320 - Azoteq 00
1. Fixed azoteq scrolling too fast.
2. Inverted the scrolling for window device.
3. Fixed the rotation of azoteq.
4. Added DRAG function for azoteq.
### 20240320 - Cirque trackpad 00
1. Added tap and scrolling features

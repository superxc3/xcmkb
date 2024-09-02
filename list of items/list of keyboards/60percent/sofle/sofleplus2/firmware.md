# Firmware
1. Flashing manual refer to [RP2040 Flashing guide](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/flashingboard.md).
2. Please press `DPI0` after you flash your firmware to activate the trackpad.

# SoflePLUS2
|![Image_20240724140025](https://github.com/user-attachments/assets/7db5fc4e-b2d2-4977-9250-ff7491b30f86)|
|:--:|
|SoflePLUS2 with smaller TPS43 trackpad, USB-C connection|

## v2.03 - Ergomech edition
- ditto v2.03
- Layer and capslock indicator changes to 5 thumb keys as RGB underglow couldnt be seen from Ergomech case
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1uCtHUZd_OpgFgbz7Knq8WT9mL4aBS1Ek/view?usp=drive_link)

## v2.03 
- Layer and capslock indicator for rgb underglow only. Using dimmer indicator color to avoid flickering.
- Able to wake from sleep
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1c0jsC7wQanfzKTrb11KxgmNjGjE4YRMC/view?usp=sharing)

## v2.02a 
- Fix issue on requiring re-plug after reboot or fresh restart by adding `#define SPLIT_WATCHDOG_ENABLE` in `config.h`.
- This is only for RGB underglow version, rgb indicator for layers and capslock remain
- This is also compatible with TPS43 trackpad, rotated.
- Add `DPI-` in `user` tab to change DPI of trackpad.
- Oled can display DPI speed now. Capslock and numlock indicator on oled is removed.
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1DG-7HxZxbw7_mIyUtNQ17sIe1OhCStHt/view?usp=drive_link)

## v2.02b - rgb indicator removed
- This is for full rgb backlighting and underglow version, rgb indicator for layers and capslock removed.
- Fix for correct visual presentation on Azoteq layout. Remove remappable dip click on the left.
- Others ditto v2.02a
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1CPBPp-_daynmbj_SM6n5wjifNQDMn945/view?usp=drive_link)

# SoflePLUS
|![image](https://github.com/user-attachments/assets/4bb93a8d-2606-4aae-afc8-74f1cbea852c)|
|:--:|
|SoflePLUS with large TPS62 trackpad, TRS connection|


## v1.02
- Fix issue on requiring re-plug after reboot or fresh restart by adding `#define SPLIT_WATCHDOG_ENABLE` in `config.h`.
- This is only for RGB underglow version, rgb indicator for layers and capslock remain
- This is for PLUS with trs connection only. C-C connection incompatible.
- TPS62 trackpad
- Add `DPI-` in `user` tab to change DPI of trackpad.
- No DPI display on OLED
- [Download](https://drive.google.com/file/d/1Rhh3cRpNw75QYf8Do9ucuipwj_ymHcOp/view?usp=drive_link)
  
## v1.02a - reported not working on 20240902
- Oled can display DPI speed now. Capslock and numlock indicator on oled is removed.
- Others ditto v1.02
- This is for PLUS with trs connection only. C-C connection incompatible.
- [Download](https://drive.google.com/file/d/1S154U7fFFqoWvL1lX_BekHu8eNVO81NM/view?usp=drive_link)

# Source Code
Keep this for personal use only. 

## v2.03 
- vial-qmk environment, pulled on 2024-09-02, compiled with qmk msys 1.9.0
- [Download](https://drive.google.com/drive/folders/1OM-pccKEOvNtJggC9Q17KyIiNZYJbKfr?usp=drive_link)

## v1.02a
- 



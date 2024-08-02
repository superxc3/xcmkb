# Firmware
Flashing manual refer to [RP2040 Flashing guide](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/flashingboard.md). 

## v2.03 - Ergomech edition
- ditto v2.03
- Layer and capslock indicator changes to 5 thumb keys as RGB underglow couldnt be seen from Ergomech case

## v2.03 
- Layer and capslock indicator for rgb underglow only. Using dimmer indicator color to avoid flickering.
- Able to wake from sleep

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
- [Download](https://drive.google.com/file/d/1CPBPp-_daynmbj_SM6n5wjifNQDMn945/view?usp=drive_link)

## v1.02
- Fix issue on requiring re-plug after reboot or fresh restart by adding `#define SPLIT_WATCHDOG_ENABLE` in `config.h`.
- This is only for RGB underglow version, rgb indicator for layers and capslock remain
- This is for PLUS with trs connection only. C-C connection incompatible.
- TPS62 trackpad
- Add `DPI-` in `user` tab to change DPI of trackpad.
- [Download](https://drive.google.com/file/d/1Rhh3cRpNw75QYf8Do9ucuipwj_ymHcOp/view?usp=drive_link)
  
## v1.02a
- Oled can display DPI speed now. Capslock and numlock indicator on oled is removed.
- Others ditto v1.02
- [Download](https://drive.google.com/file/d/1S154U7fFFqoWvL1lX_BekHu8eNVO81NM/view?usp=drive_link)

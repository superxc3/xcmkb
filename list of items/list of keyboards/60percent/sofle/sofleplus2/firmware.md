# Firmware

## v2.02a
- Fix issue on requiring re-plug after reboot or fresh restart by adding `#define SPLIT_WATCHDOG_ENABLE` in `config.h`.
- This is only for RGB underglow version, rgb indicator for layers and capslock remain
- This is also compatible with TPS43 trackpad, rotated.
- This retains `user` configuration to change DPI of trackpad. Oled can display DPI speed now. Capslock and numlock indicator on oled is removed.
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.

## v2.02b
- This is for full rgb backlighting and underglow version, rgb indicator for layers and capslock removed.
- Fix for correct visual presentation on Azoteq layout. Remove remappable dip click on the left.
- Others ditto v2.02a

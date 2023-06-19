# Firmware revision of Avalanche

## Rev3 RGB (vial-rev3-rgb)
- As Rev3 but with RGB enabled
- RGB lighting limits to Rainbow mood, Static gradient, Rainbow swirl
- Mousekey disabled
- `KEY_OVERRIDE_ENABLE = no` in `rules.mk` to reduce 1500 bytes memory.
- Please download hex [xcmkb_avalanche_v4_vial-rev3-rgb](https://drive.google.com/drive/folders/1diydoEG7hFadaGKZdStQmrYzxvltp0B7?usp=sharing), flash left and right respectively. Refer to [How to flash split](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md).

## Rev3 (vial-rev3)
- Ported to VIAL
- 4 layers (Layer 0,1,2,3)
- OLED indicator master as layer, capslock, numlock, scrlock; slave as logo
- RGB disabled
- QMK settings, combo, tap dance disabled
- Mousekey enabled
- split_usb_detect disabled to solve keyboard wake normally without plug/unplug the keyboard after restart

The firmware size is approaching the maximum - 28206/28672 (98%, 466 bytes free). You may disabled mousekey and enable QMK settings as exchange. To further customise the firmware, please copy [raw file](https://drive.google.com/drive/folders/1awaCAcurTaYuFr4dtErU9KL0yhRumAU5?usp=sharing) to `vial-qmk>keyboards>xcmkb>avalanche>v4>keymaps>vial-rev3`; make by `qmk compile -kb xcmkb/avalanche/v4 -km vial-rev3`. You need to [setup vial environment](https://get.vial.today/docs/porting-to-vial.html). 

Board is pre-flashed, please refer to [How to flash split](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md) if you are re-writing your own firmware. 



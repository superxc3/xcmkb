# Firmware revision of Avalanche

## Rev3 (vial-rev3)
- Ported to VIAL
- 4 layers (Layer 0,1,2,3)
- OLED indicator master as layer, capslock, numlock, scrlock; slave as logo
- RGB disabled
- QMK settings, combo, tap dance disabled
- Mousekey enabled
- split_usb_detect disabled to solve keyboard wake normally without plug/unplug the keyboard after restart

The firmware size is approaching the maximum - 28206/28672 (98%, 466 bytes free). You may disabled mousekey and enable QMK settings as exchange. To further customise the firmware, please copy [raw file](https://drive.google.com/drive/folders/1awaCAcurTaYuFr4dtErU9KL0yhRumAU5?usp=sharing) to `vial-qmk>keyboards>xcmkb>avalanche>v4>keymaps>vial-rev3`; make by `qmk compile -kb xcmkb/avalanche/v4 -km vial-rev3`. You need to [setup vial environment](https://get.vial.today/docs/porting-to-vial.html). 



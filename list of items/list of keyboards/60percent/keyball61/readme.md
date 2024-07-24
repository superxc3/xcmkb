# Keyball 61
Please leave feedback to us if you found any issues. If you intend to update your firmware, please check [Flashing RP2040 Uf2](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/flashingboard.md). Layout can preload from [here](https://drive.google.com/file/d/1ZNjguHmwGigQJ9IpzdkbI_sLDvHiMkt5/view?usp=drive_link).

## Special Keycodes
Created especially for trackball. Please refer to [Special Keycodes](https://github.com/idank/qmk_firmware/blob/dev-rp2040/keyboards/keyball/lib/keyball/keycodes.md).

## Firmware changelog

### v1.02
1. Let LED off when sleep
```
#define RGBLIGHT_SPLIT
#define RGBLIGHT_SLEEP 			//Turn off LEDs when computer sleeping (+72)
#define RGB_DISABLE_WHEN_USB_SUSPENDED //As RGB light does not sleep, alternative code
```
2. [Downnload](https://drive.google.com/file/d/1z029VRAnYXVFQ3z6HQBAIs96kgq-sYs1/view?usp=drive_link)

### v1.01
1. Correction on Vial keycodes as some are not working. Add SNIP in user tab.
2. Add SNIP in layer 2.
3. Enable split rgb.
4. Enable media keys.
5. [Download](https://drive.google.com/file/d/1Y9Di4MhtI9igfosnx0lmt8xSR31bet5c/view?usp=drive_link)
   
### v1.0
1. Ported to vial by referring to [idank](https://github.com/idank/qmk_firmware/tree/dev-rp2040/keyboards/keyball/keyball61).
2. 10 layers
3. Qmk settings enabled, mousekey enabled, 32 tap dances, 32 combos, 32 key overrides
4. NKRO enabled
5. Enabled other features like SPACE CADET, MAGIC which previously disabled due to restriction on atmega32u4
   

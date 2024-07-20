# Keyball 61

## Special Keycodes
Created especially for trackball. Please refer to [Special Keycodes](https://github.com/idank/qmk_firmware/blob/dev-rp2040/keyboards/keyball/lib/keyball/keycodes.md).

## Firmware changelog

### v1.02
1. add so it goes to sleep
```
#define RGBLIGHT_SPLIT
#define RGBLIGHT_SLEEP 			//Turn off LEDs when computer sleeping (+72)
#define RGB_DISABLE_WHEN_USB_SUSPENDED //As RGB light does not sleep, alternative code
```

### v1.0
1. Ported to vial by referring to [idank](https://github.com/idank/qmk_firmware/tree/dev-rp2040/keyboards/keyball/keyball61).
2. 10 layers
3. Qmk settings enabled, mousekey enabled, 32 tap dances, 32 combos, 32 key overrides
4. NKRO enabled
5. Enabled other features like SPACE CADET, MAGIC which previously disabled due to restriction on atmega32u4
   

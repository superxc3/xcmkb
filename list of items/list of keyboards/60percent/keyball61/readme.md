# Keyball 61/44/39
Please leave feedback to us if you found any issues. If you intend to update your firmware, please check [Flashing RP2040 Uf2](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/flashingboard.md). Layout can preload from [Keyball61vial](https://drive.google.com/file/d/1ZNjguHmwGigQJ9IpzdkbI_sLDvHiMkt5/view?usp=drive_link), [Keyball44vial](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/layout44.vil?v=1733385186).

## Latest firmware: v2.00🆕
![image](https://github.com/user-attachments/assets/62b93787-6e6f-46b8-94dd-34addea8ba7e)

1. Ported with Vial
2. 10 layers from Layer 0 to Layer 9
3. Layer 2: Snip layer (cursor moves very slow in this layer) [^1]
4. Layer 3: Scroll layer (cursor scroll in this layer) [^2]
5. Mediakeys enabled etc.
6. [Keyball61](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/keyball_keyball61_vial-v2.00.uf2?v=1733382765), [Keyball44](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/keyball_keyball44_vial-v2.00.uf2?v=1733385183), [Keyball39](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/keyball_keyball39_vial-v2.00.uf2?v=1733385286).

[^1]: Changing this requires qmk compilation. Configure this in lib/keyball.c, if (get_highest_layer(state) == 2) {keyball_set_cpi(CPI_SNIP); }
[^2]: Ditto, layer_state_t layer_state_set_user(layer_state_t state) { keyball_set_scroll_mode(get_highest_layer(state) == 3);

### Keycodes by XCMKB
| **Keycode** | **Function**                                                                                                   |
|-------------|---------------------------------------------------------------------------------------------------------------|
| **KBRST**   | Reset trackball configuration to CPI 500 and default scrolling speed.                                          |
| **KBSAVE**  | Save your current trackball configuration. This saved configuration will load on the next restart; otherwise, it defaults to the trackball's original settings. |
| **CPI+**    | Increase CPI by 100 for faster cursor movement (maximum CPI: 12,000).                                         |
| **CPI-**    | Decrease CPI by 100 for slower cursor movement (minimum CPI: 100).                                            |
| **CPI++**   | Increase CPI by 1,000 for super-fast cursor movement (maximum CPI: 12,000).                                   |
| **CPI--**   | Decrease CPI by 1,000 for super-slow cursor movement (minimum CPI: 100).                                      |
| **SCRMO**   | Hold to enable scrolling mode.                                                                                |
| **SCRTO**   | Toggle scrolling on or off.                                                                                   |
| **SNIP**    | Hold to reduce cursor speed for precision (sniping).  |
| **SNIPTO**  | Toggle to reduce cursor speed for precision (sniping).  |


### Changes from previous version
1. Fix wake up keyboard that requires re-plug `#define SPLIT_WATCHDOG_ENABLE`.
2. Fix `SCRTO` so we can toggle scroll properly now.

Please report any issues with the firmware to us via email at [xcmkbtech@gmail.com](mailto:xcmkbtech@gmail.com).

---

## Firmware changelog

### v2.1 beta for Keyball39
Requested by client to add 64 combo and tap dance. Trying to fix replug with `#define USB_VBUS_PIN GP19` instead. 

### v1.02
1. Let LED off when sleep
```
#define RGBLIGHT_SPLIT
#define RGBLIGHT_SLEEP 			//Turn off LEDs when computer sleeping (+72)
#define RGB_DISABLE_WHEN_USB_SUSPENDED //As RGB light does not sleep, alternative code
```
2. [Download](https://drive.google.com/file/d/1z029VRAnYXVFQ3z6HQBAIs96kgq-sYs1/view?usp=drive_link)
3. Special gateway to Keyball39 v1.02 [Download](https://drive.google.com/file/d/1WGBTCxgcSJNxjMod5waWxutPEIhL-rQC/view?usp=drive_link)

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
   

# Bastard Charybdis Nano

| ![DSC09691](https://github.com/superxc3/xcmkb/assets/79617315/5d484417-5e8b-4b37-aac5-1b1dec8f64d0) |
|:--:|
| *3D: Marble PLA, Keycaps: MT3 BOW* |

## TLDR
1. Do not remove trs/trrs cable when usb c still connecting to your pc, this will brick the mcu and board wont be function.
2. Usb-c connects to right only (trackball side).
3. Key remap uses this firmware/web: [Vial](https://get.vial.today/).
4. If you are new to vial, do refer [Basic vial layout](https://xcmkb.com/pages/basic-vial-usage).
5. Wireless build please read and fork [zmk-config-charybdis_nano](https://github.com/superxc3/zmk-config-charybdis_nano).

## Firmware

|![image](https://github.com/superxc3/xcmkb/assets/79617315/8a6cf729-c3fc-4ee1-bd64-79a74d426b58)|
|:--:|
| *Standard firmware: v3.1xcmkb (6/12/2023)* |

Default keymap inspired from Miryoku layout and defined by Bastard Keyboards. This version uses TRRS cable instead of TRS cable. 

Vial ported by XCMKB with:
- 7 layers
- qmk settings enabled (change your tapping term and tick ignore mod tap interrupt here under Tap-Hold)
- 32 tap dance, combo, key overrides
- OSM re-enabled
- Unique user code for trackball

#### Unique user code for trackball
1. DPI+ : the pointer moves faster
2. DPI- : the pointer moves slower
3. SNPI+ : snip moves faster
4. SNPI- : snip moves slower
5. SNP : hold to snip. snip is used for small precision pointing. when we need to point or select on small thing, we use snip
6. SNPT : toggle snip on and off
7. DRG : hold to scroll
8. DRGT : toggle scroll on and off



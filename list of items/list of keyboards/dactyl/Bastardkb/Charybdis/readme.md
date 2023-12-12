# Charybdis 4x6
Default keymap inspired from Miryoku layout and defined by Bastard Keyboards. This version uses TRRS cable instead of TRS cable. List of firmware utilized with Vial enabled, modified from Bastardkb. These are proprietary components, and we have chosen not to disclose the source code.
  - [Default vial firmware (20231212)](#default-vial-firmware-20231212)
  - [v3.0xcmkb - Full Vial Ported 20231202](#v30xcmkb---full-vial-ported-20231202)


## Firmware

### Default vial firmware (20231212)
This is the standard firmware ported with Vial
- 4 layers only
- qmk settings enabled
- tap dance, combo, key overrides enabled
- default user code for trackball provided by bastardkeyboard
  

### v3.0xcmkb - Full Vial Ported 20231202
Default keymap inspired from Miryoku layout and defined by Bastard Keyboards. This version uses TRRS cable instead of TRS cable. Hand configuration changes from splinky_31/config.h

Vial ported by XCMKB with:
- 7 layers
- qmk settings enabled (change your tapping term and tick ignore mod tap interrupt here under Tap-Hold)
- 32 tap dance, combo, key overrides
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

#### Known issue
a. USB-C connects to right only.

```qmk compile -kb bastardkb/charybdis/4x6/v2/splinky_3 -km vial```~~

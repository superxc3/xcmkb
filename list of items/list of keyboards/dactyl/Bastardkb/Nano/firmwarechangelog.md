# Firmware Changelog
Default firmware: [v0.2](#v02-xcmkb---splinktegrated--2024-01-05-)

## List of firmware
- [v3.1xcmkb - OSM re-enabled (2023-12-06)](#v31xcmkb---osm-re-enabled-2023-12-06) This is for old batch 
- [v3.0xcmkb - Full Vial Ported (2023-12-02)](#v30xcmkb---full-vial-ported-2023-12-02) This is for old batch 
- [Flashing UF2 Guide](#flashing-uf2-guide)

## v0.2 xcmkb - splinktegrated (2024-01-05)
- Change of mcu to splinktegrated
- Rename info.json

## v0.3 xcmkb - auto-mouse layer, left as main (2024-01-23) - not using
This version is omitted as plugging in left trackball is unstable for scroll function etc. Auto-mouse layer is also not stable and hard to control. 

- Enable auto-mouse layer, touch the trackball auto-trigger mouse layer
- Plug in left and trackball still working great 
- Notes for xc: `qmk compile -kb bastardkb/charybdis/3x5/v2/splinky_3vial -km vial`

# Flashing UF2 Guide

## Steps

1. **Download Firmware:**
   - Download the firmware files for the left and right sides from the link provided by XC.

2. **Turn On VIAL:**
   - Launch the VIAL software.

5. **Double Press Reset Button:**
   - Locate the reset button on the bottom of each PCB. Double press the reset button on one side.

6. **Flash Left Side:**
   - A window explorer will open. Drag the left UF2 firmware file into the folder and wait until the board appears in the VIAL software.

7. **Repeat for Right Side:**
   - Double press the reset button on the other side and drag the right UF2 firmware file into the folder. Wait for the board to appear in the VIAL software.

8. **Flashing Complete:**
   - Once both sides are recognized by VIAL, the flashing is done.


:exclamation: *Do not disconnect or connect the TRS/TRRS cable while the USB C is still connected to the PC to avoid MCU brick.*



# Firmware Changelog
- [v3.1xcmkb - OSM re-enabled (2023-12-06)](#v31xcmkb---osm-re-enabled-2023-12-06)
- [v3.0xcmkb - Full Vial Ported (2023-12-02)](#v30xcmkb---full-vial-ported-2023-12-02)
- [Flashing UF2 Guide](#flashing-uf2-guide)

## v3.1xcmkb - OSM re-enabled (2023-12-06)
- Main change: Uncomment `NO_ACTION_ONESHOT` to enable OSM under `C:\Users\xcmkb\vial-qmk\keyboards\bastardkb\charybdis\3x5\keymaps\vial\config.h`.

## v3.0xcmkb - Full Vial Ported (2023-12-02)
- Hand configuration changes from `splinky_31/config.h`, change `MASTER_LEFT` or `RIGHT` before individual compilation.
- Make command `qmk compile -kb bastardkb/charybdis/4x6/v2/splinky_31 -km vial`


# Flashing UF2 Guide

## Steps

1. **Download Firmware:**
   - Download the firmware files for the left and right sides from the link provided by XC.

2. **Disconnect from PC:**
   - Unplug the USB C cable from your split keyboard, ensuring it's completely disconnected from your computer.

3. **Disconnect Splits:**
   - Unplug the TRS or TRRS cable connecting the two halves of your split keyboard.
     
4. **Turn On VIAL:**
   - Launch the VIAL software.

5. **Double Press Reset Button:**
   - Locate the reset button on the bottom of each PCB. Double press the reset button on one side.

6. **Flash Left Side:**
   - A window explorer will open. Drag the left UF2 firmware file into the folder and wait until the board appears in the VIAL software.

7. **Repeat for Right Side:**
   - Double press the reset button on the other side and drag the right UF2 firmware file into the folder. Wait for the board to appear in the VIAL software.

8. **Flashing Complete:**
   - Once both sides are recognized by VIAL, the flashing is done.

9. **Reconnect Cables:**
   - Reconnect the TRS or TRRS cable between the two halves of your split keyboard.
   - Reconnect the USB C cable to your computer.

10. **Done:**
    - Your split keyboard is now successfully flashed with the new firmware.

:exclamation: *Do not disconnect or connect the TRS/TRRS cable while the USB C is still connected to the PC to avoid MCU brick.*



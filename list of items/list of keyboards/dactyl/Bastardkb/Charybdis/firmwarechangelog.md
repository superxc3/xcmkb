# Firmware Changelog

List of firmware utilized with Vial enabled, modified from Bastardkb. These are proprietary components, and we have chosen not to disclose the source code.
- [Default vial firmware: v0.3](#v0.2-20240125)
- [Default vial firmware: v0.2](#v0.2-20240105)


## List of firmware
- [Flashing UF2 Guide](#flashing-uf2-guide)
- [Flashing UF2 Guide without physical reset button](#flashing-uf2-guide-without-physical-reset-button)

### v0.3 (20240125)
- adds layer number from 4 to 7, namely 0123456
- auto-mouse layer enabled, green light up when layer is triggered.
- free to use and [download](https://drive.google.com/file/d/1_PwiKGskKvhrY-eqHm3sat8IGjYGmofS/view?usp=drive_link).
- 7 layers without automouse [download](https://drive.google.com/file/d/1bn51Q2Pfrlb3xfuxXCjeV9rA-oBIvpXs/view?usp=drive_link).

#### Known bug
- rgb lightning resets to maximum brightness after auto-mouse layer is triggered

### v0.2 (20240105)
- splinktegrated, no longer rp2040 promicro
- re-enabled osm

### v0.1 (20231212)
This is the standard firmware ported with Vial
- 4 layers only
- qmk settings enabled
- tap dance, combo, key overrides enabled
- default user code for trackball provided by bastardkeyboard


# Flashing UF2 Guide

## Steps

1. **Download Firmware:**
   - Download the firmware files from the link provided by XC.

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

# Flashing UF2 Guide without physical reset button
1. **Download Firmware:**
   - Download the firmware files from the link provided by XC.

2. **Disconnect from PC:**
   - Unplug the USB C cable from your split keyboard, ensuring it's completely disconnected from your computer.

3. **Disconnect Splits:**
   - Unplug the TRS or TRRS cable connecting the two halves of your split keyboard.
     
4. **Turn On VIAL:**
   - Launch the VIAL software.

5. **Double Press Reset Button:**
   - Since you cant reach your reset button, assign a `reset` key under `quantum` tab, double press it.
   - ![image](https://github.com/superxc3/xcmkb/assets/79617315/07247481-d3b3-4117-84a6-61a5754017e3)

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

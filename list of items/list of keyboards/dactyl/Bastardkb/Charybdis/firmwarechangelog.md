# Firmware Changelog
Default firmware: v0.2

## List of firmware
- [Flashing UF2 Guide](#flashing-uf2-guide)
- [Flashing UF2 Guide without physical reset button](#flashing-uf2-guide-without-physical-reset-button)


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

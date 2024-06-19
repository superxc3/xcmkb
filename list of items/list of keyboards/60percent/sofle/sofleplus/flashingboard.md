# Flashing RP2040 Uf2

## Save keymap before reset
If you already remap the keys, please save layout before flashing. 
![image](https://github.com/superxc3/xcmkb/assets/79617315/29c79087-a6ec-444a-b77b-39ec0b25a0e7)

### Split Keyboard
1. Get ready of your compiled firmware or uf2 we provided. 
2. No QMK toolbox is required.
3. Double-press the reset button between the OLED and TRS jack at the inner side of the board.
4. Drag the uf2 file to new window you just called out.
![image](https://github.com/superxc3/xcmkb/assets/79617315/b64efa1e-6ed9-47e8-b252-9e590b9865eb)
5. Wait for about 5s for the board to be flashed (when key can be registered after you dragged the file in then it is done)
6. That should be considered done for the left split. Continue the step above for the RIGHT split.
12. Done!
13. Load saved layout in Vial you have saved your keymap.

Now you can start testing your new firmware. Have fun!

### Notes for Trackpad V1.01 version
1. Please press `DPI0` after you flashed your firmware to activate the trackpad.
2. Plug in usb left oled shows wpm rocket, plug in usb to right oled shows overall status. 

# Flashing RP2040 Uf2

## Save keymap before reset
If you already remap the keys, please save layout before flashing. 
![image](https://github.com/superxc3/xcmkb/assets/79617315/29c79087-a6ec-444a-b77b-39ec0b25a0e7)

### Split Keyboard
1. Get ready of your compiled firmware or download from [Standard Firmware for SoflePLUS](https://drive.google.com/drive/u/0/folders/1vNPOlv2NhzNlO9qoJ0fS3oOtKQtKS7rQ); [Standard Firmware for Corne](https://drive.google.com/drive/u/0/folders/1-6yim1sLNgdcoQgKbDtAbBsG6yMPpH2_).
2. Disconnect your board from pc by unplugging the micro usb or type c cable. 
3. Disconnect your splits by unplugging the trs or trrs cable. 
4. No QMK toolbox is required.
6. Re-connect your LEFT split to pc, no trs cable is inserted yet.
7. Double-press the reset button between the OLED and TRS jack at the inner side of the board.
   
8. Drag the uf2 file to new window you just called out.
![image](https://github.com/superxc3/xcmkb/assets/79617315/b64efa1e-6ed9-47e8-b252-9e590b9865eb)

10. Wait for about 5s for the board to be flashed (when key can be registered after you dragged the file in then it is done)
11. That should be considered done for the left split. Continue the step above for the RIGHT split.
12. Done!
13. Unplug your right split. Connect your splits through trs, reconnect usb c to either side.
14. Load saved layout in Vial you have saved your keymap.

Now you can start testing your new firmware. Have fun!

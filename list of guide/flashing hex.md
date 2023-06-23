# Flashing Hex

## Save keymap before reset
If you already remap the keys, please save layout before flashing. 
![image](https://github.com/superxc3/xcmkb/assets/79617315/29c79087-a6ec-444a-b77b-39ec0b25a0e7)


When you are given a new hex file to flash, kindly follow the steps below closely. 

For [single keyboard](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md#single-keyboard), you can just proceed with following session. 
For [split keyboard](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/flashing%20hex.md#split-keyboard), kindly refer to another session below. 

### Single Keyboard
1. Download [QMK TOOLBOX](https://github.com/qmk/qmk_toolbox/releases); for Win platform download [here](https://github.com/qmk/qmk_toolbox/releases/download/0.1.1/qmk_toolbox.exe)
2. Get your hex ready. 
3. Locate file by click Open in QMK Toolbox
4. Select atmega32u4 for MCU
5. Tick Auto-flash

![image](https://user-images.githubusercontent.com/79617315/151154592-66fd339c-c9e2-426d-813c-5745424c3f6c.png)

7. Connect your board to PC. Check the reset button (Sofle and corne near to oled; while some boards are at the bottom)
8. When everything is selected and ticked as Step 5, double press the reset button. 
9. Done


### Split Keyboard
1. Disconnect your board from pc by unplug the micro usb or type c cable. 
2. Then only disconnect your splits by unplug the trs or trrs cable. 
3. Download [QMK TOOLBOX](https://github.com/qmk/qmk_toolbox/releases); for Win platform download [here](https://github.com/qmk/qmk_toolbox/releases/download/0.1.1/qmk_toolbox.exe)
4. Get your hex ready. 
5. Locate file by click Open in QMK Toolbox
6. Select atmega32u4 for MCU
7. Tick Auto-flash

![image](https://user-images.githubusercontent.com/79617315/151154592-66fd339c-c9e2-426d-813c-5745424c3f6c.png)

8. Connect your LEFT split to pc. Check the reset button (Sofle and corne near to oled; while some boards are at the bottom)
9. When everything is selected and ticked as Step 7, double press the reset button. 
10. That should be considered done for left split. Continue the step above for right split, do note that some split requires different hex file to enable master on left and right.
11. After you have flashed the board and everything is working, please refer to **Save keymap before reset** to `load saved layout` in Vial. 

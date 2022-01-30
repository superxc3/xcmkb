# User Manual for Sofle ZMK Wireless

This user manual is applicable for Sofle V1, V2, and Choc version. They are basically using the same firmware. 

The board is already preflashed with ZMK. However to remap the keys, users must learn how to setup zmk environment. Kindly refer to [this link](https://zmk.dev/docs/development/setup) for zmk setup. 

The board can be clicky when connecting it to your PC. Do proceed with Part A when you receive your wireless unit. 

## Part A Connect to your PC
1. Clear Bluetooth profile

|![image](https://user-images.githubusercontent.com/79617315/151686442-9965558d-bbb1-497a-a1aa-7a2406a442d9.png)|
|:--:|
|For Sofle ZMK, clear your bluetooth profile by clicking the left knob (means BTCLR)|

|![image](https://user-images.githubusercontent.com/79617315/151686605-3673bf43-e9b2-4f76-9c8a-d4a996859393.png)|
|:--:|
|For Corne ZMK, LWR+BTCLR as keymap above|

2. For Win platform, START> Bluetooth & other devices
3. Add Bluetooth or other device > Bluetooth > Corne should be appeared in the list
4. Connect and done. Test if left and right are responding. If not proceed with Part B

## Part B Flash zmk
1. Connect left and right splits to your pc (both connect together using type c cable)
2. Put right into bootloader mode (press the reset button), one window is popped out showing "nicenano" folder. Dont do anything yet, remember this folder as right split. 
3. Now press reset button on your left split, one window will be popped out as previous step.
4. Drag [Sofle right_u2f](https://drive.google.com/file/d/1vG_Vt5kh-t4oU3vA74P0v6XJFsQKFMX0/view?usp=sharing) for Sofle and [Corne right u2f](https://drive.google.com/file/d/1mlszON0ekp84vhrinADzJo_43td5rVRl/view?usp=sharing) for Corne to right split nicenano folder, the window will be closed once you dragged the u2f file in.
5. Do not disconnect right split yet. 
6. Now drag [Sofle left u2f](https://drive.google.com/file/d/1aMdDRVfslyowl-SOPlrPt2pp_X3KuXlv/view?usp=sharing) for Sofle and [Corne left u2f](https://drive.google.com/file/d/1EGCXd9WICUCVBMP7et7vqlWj9Ho8sg_N/view?usp=sharing) for Corne to the remaining nicenano folder. 
7. Remove left split from type c cable. Proceed with Part A to connect your board to pc. If successfully connected, you shall able to type without cable now. 
8. If so, remove the right split from type c cable. Both should be working good now!

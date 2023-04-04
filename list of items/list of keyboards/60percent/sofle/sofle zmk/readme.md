# User Manual for Sofle ZMK Wireless

This user manual is applicable for Sofle V1, V2, and Choc version. They are basically using the same firmware. 

For boards after 2023.04.04, it is flashed with `infused-kim` repo which supports both sides rotary encoders. Please fork [this link](https://github.com/superxc3/zmk-config-sofle) and follow the instruction for key remap.



~The board is already preflashed with ZMK. However to remap the keys, users must learn how to setup zmk environment. Kindly refer to [this link](https://zmk.dev/docs/development/setup) for zmk setup.~

The board can be tricky when connecting it to your PC. Do proceed with Part A when you receive your wireless unit. 

## Part A Connect to your PC
![sofle connection](https://user-images.githubusercontent.com/79617315/229803261-facdd50c-475b-4ff5-9293-e3c17da099f0.jpg)

## Part B Flash zmk
1. Connect left and right splits to your pc (both connect together using type c cable)
2. Put right into bootloader mode (press the reset button), one window is popped out showing "nicenano" folder. Dont do anything yet, remember this folder as right split. 
3. Now press reset button on your left split, one window will be popped out as previous step.
4. Drag [Sofle right_u2f](https://drive.google.com/file/d/1vG_Vt5kh-t4oU3vA74P0v6XJFsQKFMX0/view?usp=sharing) for Sofle and [Corne right u2f](https://drive.google.com/file/d/1mlszON0ekp84vhrinADzJo_43td5rVRl/view?usp=sharing) for Corne to right split nicenano folder, the window will be closed once you dragged the u2f file in.
5. Do not disconnect right split yet. 
6. Now drag [Sofle left u2f](https://drive.google.com/file/d/1aMdDRVfslyowl-SOPlrPt2pp_X3KuXlv/view?usp=sharing) for Sofle and [Corne left u2f](https://drive.google.com/file/d/1EGCXd9WICUCVBMP7et7vqlWj9Ho8sg_N/view?usp=sharing) for Corne to the remaining nicenano folder. 
7. Remove left split from type c cable. Proceed with Part A to connect your board to pc. If successfully connected, you shall able to type without cable now. 
8. If so, remove the right split from type c cable. Both should be working good now!

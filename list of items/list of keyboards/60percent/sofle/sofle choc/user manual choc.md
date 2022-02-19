# User Manual for Sofle Choc version

|![image](https://user-images.githubusercontent.com/79617315/151686143-a4a06e3f-44ec-421c-bcf1-bf22fa05fb73.png)|
|:--:|
|Sofle Choc with RGB per key Black Matte Edge Design|

|![image](https://user-images.githubusercontent.com/79617315/151686145-17df9e7e-0006-426c-9091-2e212c9b033d.png)|
|:--:|
|Pinky Sofle Choc ZMK Wireless version Limited Run|


This user manual is specially written for choc version due to minor changes from typical Sofle. 
- For sofle choc without rgb, kindly refer to [user manual for Sofle](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/user%20manual.md#user-manual-for-sofle). Basically choc without rgb is using the same firmware as sofle v1 and v2. 
- For sofle choc with rgb, there is minor difference hence refer to the session below. 

## Part A Connect 

### Step 1 
Connect both splits by using the TRS cable provided. Make sure it is properly inserted. 
![image](https://user-images.githubusercontent.com/79617315/150457931-cd488d1e-3cb7-4ce3-a2a7-16cdad78e0e2.png)

### Step 2 
Connect your micro usb / Type C / magnetic cable to left of the split. Currently it is supported for left split as master only, meaning usb only can connect to the left split. 


#### Warnings and disclaimers
- Don’t connect or disconnect the TRS or aux cable when the keyboard is powered. It may short out. Always disconnect the USB cable first.
- Make sure your cable is a data usb cable, i.e. can transmit data. 
- If you are using a micro usb sofle, be gentle with micro USB ports on your microcontrollers. They are easy to break. 
- Recommended to pair with magnetic cable. Ugreen magnetic cable can be purchased from local MY store through Shopee: [Official UGreen](https://shopee.com.my/UGREEN-3A-Magnetic-Micro-USB-Cable-(100cm)-i.64923440.1619064012?sp_atk=90a0daf5-02a6-424b-93f6-f23fec3c7efe) (may take a week to arrive); [local Ugreen store](https://shopee.com.my/%F0%9F%87%B2%F0%9F%87%BE-UGREEN-Magnetic-Micro-USB-Cable-Fast-Charging-1-Meter-Nylon-Braided-Data-Magnet-USB-Cable-%F0%9F%87%B2%F0%9F%87%BE-i.24857778.9586773643?sp_atk=d176ec5a-5417-4007-ab65-a17f9fa2b2ad) (purchased and legit).
- Always set the brightness of RGB per key to 50% of lower, over power drawn might happened if you set above that or to 100%. Your boards will just disconnect from the pc. This is a common issue for RGB per key board.


## Part B Assemble 
For MX version, you are required to remove the switch plate and insert the switch one by one. However for choc version, you can just insert the switch directly. 


## Common issues
#### Oled is up but key cannot be registered
Most of the time the problem would be USB cable. Recommend to find a more reliable data cable or just purchase the Ugreen magnetic cable as suggested above. 

#### Master split is working perfectly, slave side is not registering
Most of the time the problem would be USB cable. Recommend to find a more reliable data cable or just purchase the Ugreen magnetic cable as suggested above. 

#### Certain keys are not registered
Check any bent pins on your switch. 

#### Board functions good in the first few second, and disconnect from pc afterward
Might be over power drawn from usb port. Lower the brightness to maximum 50%. 


## Part C Key Remap
### VIA
1. Sofle is built on top of QMK and officially supported by VIA. Once you connect the board to PC, it will be automatically detected in VIA. 

![image](https://user-images.githubusercontent.com/79617315/150453274-56f37c4d-e0c8-416a-886d-4fadf961090b.png)

2. VIA software downloads from [here](https://github.com/the-via/releases/releases/tag/v1.3.1).
[Windows platform download here](https://github.com/the-via/releases/releases/download/v1.3.1/via-1.3.1-win.exe). 

4. VIA is a real-time mapping software. Saving is not required and it will be reflect directly once you have assigned the key.

5. You can save your layout in case you want to format the board. Else the board has memory on board and does not required to remap the key although connect to different pc. 

![image](https://user-images.githubusercontent.com/79617315/150453954-8d949cf6-fcf2-4673-8b22-b27a6101c779.png)


#### Notes
- Do launch one application each time to avoid conflict. 
- Currently the knobs are fixed at left for volume, right for page up and down. 
- Sofle choc only supports choc v1. Choc v2 is not supported by the pcb. 



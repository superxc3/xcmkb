# User Manual for Sofle

This user manual is applicable for Sofle V1 and V2.
Before proceed to assemble your board with switches and keycaps, you can try with [Part A](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/user%20manual.md#part-a-connect) to test out your sofle unit. We tested the board before shipping, this include TRS cable, key registration, oleds, knobs, and magnetic cable (if you purchase one from us). 

## Part A Connect 

### Step 1 
Connect both splits by using the TRS cable provided. Make sure it is properly inserted. 
![image](https://user-images.githubusercontent.com/79617315/150457931-cd488d1e-3cb7-4ce3-a2a7-16cdad78e0e2.png)

### Step 2 
Connect your micro usb / Type C / magnetic cable to either left or right side of the split. Our units are properly flashed, both splits can be used as master. 

*Pimoroni only working for master side. Let's say you have pimoroni installed on your right, the master must be right.*
![image](https://user-images.githubusercontent.com/79617315/150458013-4cbabd64-f0ea-4947-93ae-89137f7cf8f1.png)


#### Warnings and disclaimers
- Don’t connect or disconnect the TRS or aux cable when the keyboard is powered. It may short out. Always disconnect the USB cable first.
- Make sure your micro usb cable is a data usb cable, i.e. can transmit data. 
- Be gentle with micro USB ports on your microcontrollers. They are easy to break. 
- Recommended to pair with magnetic cable. Ugreen magnetic cable can be purchased from local MY store through Shopee: [Official UGreen](https://shopee.com.my/UGREEN-3A-Magnetic-Micro-USB-Cable-(100cm)-i.64923440.1619064012?sp_atk=90a0daf5-02a6-424b-93f6-f23fec3c7efe) (may take a week to arrive); [local Ugreen store](https://shopee.com.my/%F0%9F%87%B2%F0%9F%87%BE-UGREEN-Magnetic-Micro-USB-Cable-Fast-Charging-1-Meter-Nylon-Braided-Data-Magnet-USB-Cable-%F0%9F%87%B2%F0%9F%87%BE-i.24857778.9586773643?sp_atk=d176ec5a-5417-4007-ab65-a17f9fa2b2ad) (purchased and legit). 


## Part B Assemble 

### Switch Plate

#### Acrylic, FR4, Aluminium, Brass switch plate  
For plates mentioned above, you can just insert the switches without dissembling the board. 

#### Polycarbonate switch plate
Polycarbonate is a strong yet soft material, you are required to unscrew and remove the switch plate. 

### Step 1
Remove the aluminium knobs by using wrench. Then, unscrew the switch plate and remove the switch plate from the board. 

### Step 2
Insert the switch one by one

### Step 3 
Make sure the orientation of switches is correct according to your pcb. 

### Step 4
After all switches are inserted, place it back to the board. Tighten the screws. Go to [Part A](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/sofle/user%20manual.md#part-a-connect) to connect your board to PC. 
![](https://user-images.githubusercontent.com/79617315/150452631-d44be381-1db2-464b-be66-542579b562e2.jpg)


## Part C Key Remap
### VIA
1. Sofle is built on top of QMK and officially supported by VIA. Once you connect the board to PC, it will be automatically detected in VIA. 

![image](https://user-images.githubusercontent.com/79617315/150453274-56f37c4d-e0c8-416a-886d-4fadf961090b.png)

2. VIA software downloads from [here](https://github.com/the-via/releases/releases/tag/v1.3.1).
[Windows platform download here](https://github.com/the-via/releases/releases/download/v1.3.1/via-1.3.1-win.exe). 

4. VIA is a real-time mapping software. Saving is not required and it will be reflect directly once you have assigned the key.

5. You can save your layout in case you want to format the board. Else the board has memory on board and does not required to remap the key although connect to different pc. 

![image](https://user-images.githubusercontent.com/79617315/150453954-8d949cf6-fcf2-4673-8b22-b27a6101c779.png)


### Programmable Rotary Encoders / Knobs through VIAL
1. Besides VIA, you also can remap using VIAL. VIAL supports remap knobs with different layers. 
2. VIAL download [here](https://get.vial.today/download/)


<s>
  
### REMAP Not recommend to use REMAP atm. 
1. REMAP is a relatively simpler key remapping website. 
2. REMAP link [here](https://remap-keys.app/)
3. The HOLD and TAP remap interface is easier using REMAP compare to VIA. However, VIA has richer content and more tapping option compared to REMAP. 

![image](https://user-images.githubusercontent.com/79617315/150454359-ab1dcfd9-7e8e-475c-ab4a-ee005d808d9b.png)
</s>


#### Notes
Do launch one application each time to avoid conflict. 


## Keycaps
There are total of 58 keys with all 1u. For 2 thumb keys you can use either 1u or 1.5u. If you don’t mind the legend doesn’t show up properly (like ctrl, alt, tab etc), you can substitute with normal keycap set with 1u novelties. Recommended to use flat profile such as xda, dsa, np etc, so that you do not need to worry about height profile issue. 

For this kind of board with all 1u, there is dedicated keycap sets. You can try to search for “ortholinear keycaps”.

## Switches 
It supports both 3/5pins mx style switches. Can look for smd type if you choose for acrylic, it can lock to the switch plate better. Milk bottom will be more loose for acrylic version. 

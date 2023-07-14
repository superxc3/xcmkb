# User Manual for Sofle

![image](https://github.com/superxc3/xcmkb/assets/79617315/1fc4084e-740a-4594-b958-ec9c65ea7c8f)

![image](https://github.com/superxc3/xcmkb/assets/79617315/3018c4f3-2c5d-474e-93aa-21701d202f28)


## What is included?
- 1 x Left and right pre-soldered Sofle
- Pre-flashed with VIAL
- 1 x TRS cable
- 2 x knobs
- 2 x oleds
- Switch plate, layers of acrylic or 3D case based on your purchase

### What is not included and you need to prepare:
1. 58 3/5 pins switches mx or kailh lp choc v1 depends on your board, recommended to get extra 1-2. 
2. 58 x 1u keycaps; 1 thumbkey on each side supports up to 1.5u
3. Type c to type a cable. Type c to c not suitable for promicro. 

### MX user
- For pom / carbon fibre switch plate, prepare switch puller. It is advised to remove the switch plate and insert the switches one by one rather than inserting them directly.
- For 3D printed switch plates, it is generally recommended to insert the switches directly without removing the switch plate.

### LP choc user
- No switch plate can properly lock the switch. When you remove the keycap, the switch will be pulled along with it. If the switch is locked in the switch plate, you can either wiggle the switch and pull it out, or disassemble the board and push the switch from the bottom of the PCB.

### Key Remap
Download [Vial](https://get.vial.today/download/) for key remap. No flashing is required unless you are purchasing build kit. Basically plug and play. 

The quantum can achieve tap feature such as: Hold as Left Control; tap as Space. Just hover on it and it will explain how it works.
![image](https://user-images.githubusercontent.com/79617315/208881636-7c6481e0-e320-4ad1-b727-bb4b7e0616f4.png)

Also layer cycle through Layer tab:
![image](https://user-images.githubusercontent.com/79617315/208881348-fc678b95-c729-4dff-94a2-946d5032845c.png)

You can refer to [Vial Tutorial](https://get.vial.today/manual/) for Layers, Macros, Tap Dance, Combos features (this is suitable for rp2040 promicro). 

### Notes
1. :warning: This step is crucial to prevent bricking the MCU. When connecting a split keyboard, it is important to ensure proper and correct connections. Please refer to [demo](https://www.instagram.com/tv/CdpYrWBJuD9/?igshid=YmMyMTA2M2Y=) here.
![image](https://user-images.githubusercontent.com/79617315/204213627-3c877043-aae7-45f9-804b-e50d5ad57624.png)
3. If you brick your MCU, your board will no longer function. You will need to replace the set of MCUs if the MCU is bricked.
4. :warning: For RGB per-key users, it is recommended to set the brightness to a maximum of 50% only. Setting it higher than that may result in an unstable power supply to the USB, potentially causing the keyboard to disconnect from your PC.
3. Common issues refer to [Common Issues](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/common%20issues.md).


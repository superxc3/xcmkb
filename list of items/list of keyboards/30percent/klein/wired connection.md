# Wired Connection
This user manual is for wired board only.

### Firmware feature
Now with [Splinky 0xB2](https://github.com/Bastardkb/Splinky) from Bastardkb or Promicro RP2040, a more powerful RP2040 MCU! Advanced firmware support:
- 7 layers,
- 32 tap dance,
- 32 combos,
- 32 key overrides,
- Qmk settings enabled
- this firmware is [xcmkb_klein_kb2040_vial_rp2040_ce](https://drive.google.com/drive/u/0/folders/11u9dBjUY0dFGJmRuhipja7L_fOKngKPu)
  

### Key Remap
Download [Vial](https://get.vial.today/download/) for key remap. No flashing is required unless you are purchasing build kit. Basically plug and play. 
![image](https://github.com/superxc3/xcmkb/assets/79617315/b52e9b8e-1c53-4f9f-836d-1c9b244849fb)

The quantum can achieve tap feature such as: Hold as Left Control; tap as Space. Just hover on it and it will explain how it works.
![image](https://user-images.githubusercontent.com/79617315/208881636-7c6481e0-e320-4ad1-b727-bb4b7e0616f4.png)

Also layer cycle through Layer tab:
![image](https://user-images.githubusercontent.com/79617315/208881348-fc678b95-c729-4dff-94a2-946d5032845c.png)

You can refer to [Vial Tutorial](https://get.vial.today/manual/) for Layers, Macros, Tap Dance, Combos features (this is suitable for rp2040 promicro). 

### LP choc user
- No switch plate can properly lock the switch. When you remove the keycap, the switch will be pulled along with it. If the switch is locked in the switch plate, you can either wiggle the switch and pull it out, or disassemble the board and push the switch from the bottom of the PCB.
  
### Notes
1. :warning: This step is crucial to prevent bricking the MCU. When connecting a split keyboard, it is important to ensure proper and correct connections. Please refer to [demo](https://www.instagram.com/tv/CdpYrWBJuD9/?igshid=YmMyMTA2M2Y=) here.
![image](https://user-images.githubusercontent.com/79617315/204213627-3c877043-aae7-45f9-804b-e50d5ad57624.png)
3. If you brick your MCU, your board will no longer function. You will need to replace the set of MCUs if the MCU is bricked.
4. :warning: For RGB per-key users, it is recommended to set the brightness to a maximum of 50% only. Setting it higher than that may result in an unstable power supply to the USB, potentially causing the keyboard to disconnect from your PC.
3. Common issues refer to [Common Issues](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/common%20issues.md).

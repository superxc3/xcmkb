# Bastard TBK Mini

TBK Mini is a Dactyl Manuform designed by Bastard. It has compact and silent design with a 3-key thumb cluster. We modified a lil bit in reducing the cost by handwiring almost everything instead of using flexible pcb from Bastard. 

## What is included
- 3d printed case
- USB c promicro
- TRS cable
- rubber feet included
- no RGB 

## What is not included and you need to preparee
- 42 mx switches
- keycaps
- usb c to usb a cable (usb c to c might not working)

## Key Remap
Key remap download [Vial](https://get.vial.today/download/). 

The quantum can achieve tap feature such as: Hold as Left Control; tap as Space. Just hover on it and it will explain how it works.
![image](https://user-images.githubusercontent.com/79617315/208881636-7c6481e0-e320-4ad1-b727-bb4b7e0616f4.png)

Also layer cycle through Layer tab:
![image](https://user-images.githubusercontent.com/79617315/208881348-fc678b95-c729-4dff-94a2-946d5032845c.png)

## Notes
1. :warning: This step is very important to avoid mcu bricked. Properly connect split keyboard refer to [Video](https://www.instagram.com/tv/CdpYrWBJuD9/?igshid=YmMyMTA2M2Y=). 
![image](https://user-images.githubusercontent.com/79617315/204213627-3c877043-aae7-45f9-804b-e50d5ad57624.png)
2. Common issues refer to [Common Issues](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/common%20issues.md).

## Firmware
The board is flashed with Vial and firmware revision can refer to [Firmware](). Do note that the board is pre-flashed so flashing is no required. If you need to compile new firmware in the future, it is in the qmk firmware under directory of `bastardkb/tbkmini/v2`, please take note of the following:

### Change the diode direction
In `config.h`, default comes with `#define DIODE_DIRECTION ROW2COL`, pleaase replace with `#define DIODE_DIRECTION COL2ROW`,

### Change bootloader 
In `rules.mk`, change the default value of `BOOTLOADER = atmel-dfu` to `BOOTLOADER = caterina`. This is very important because you may brick your mcu if you did not change to correct bootloader or flash with correct bootloader. 



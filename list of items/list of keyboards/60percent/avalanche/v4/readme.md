# Avalanche V4

![avalanche](https://user-images.githubusercontent.com/79617315/204091295-ad4ab703-b964-4418-b809-15c3c8a2a32a.jpg)

## Avalanche v4.2 
- 60% split keyboards
- hotswap mx 3/5pins
- 4x6 keys, 1 additional key on the left, 2 additional keys for the index finger, 4 thumb keys each side (total 31x2=62)
- 3D printed Switch Plate
- 2 x 0.96inch larger Oled
- 2 x rotary encoder with full aluminium premium knob
- Programmable through VIAL
- Socketed USB C promicro
- 3D printed case and oled cover included
- TRS cable included

### Notes
- rgb per key up-gradable but service not provided atm
- rgb underglow not available as per design 

### What is not included and you need to prepare:
1. 62 mx switches (3/5pins)
2. 62 x 1u keycaps
3. type c cable

### User Manual
1. Key remap download [Vial](https://get.vial.today/download/). 
2. :warning: This step is very important to avoid mcu bricked. Properly connect split keyboard refer to [Video](https://www.instagram.com/tv/CdpYrWBJuD9/?igshid=YmMyMTA2M2Y=). 
3. Common issues refer to [Common Issues](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/common%20issues.md).

### Firmware (Wired)
The board is not officially supported by VIA. Customisation for VIAL has been done by XCMKB. The qmk github provided by author refer to [here](https://github.com/qmk/qmk_firmware/tree/master/keyboards/avalanche/v4). The list of firmware revision please refer to [Avalanche Firmware Revision](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/avalanche/v4/firmware.md). 

#### OLED
The default oled was "Avalanche V4.2". Re-configured as follow with new logo and indicators. 
![WeChat Image_20221126212229](https://user-images.githubusercontent.com/79617315/204091127-62cf6cbc-6d90-425d-82d8-cc8b118d7553.jpg)

### Firmware (Wireless)
This is only working for bluetooth avalanche with nicenano v2 mcu. Oled and rgb per key are not supported. The board you received is already flashed with zmk uf2. To connect the board, please refer to the step below:

:construction: This part is still in construction.

If you wish to remap the key, kindly refer to [Zmk Setup](https://zmk.dev/docs/development/setup). The zmk environment of avalanche has been setup by [Roman Florea](https://github.com/romones/zmk-config). Everything is working except the avalanche_right.overlay as one of his nicenano mcu pin fired. It is clearly stated in the document.

Replace	`//, <&pro_micro 18 GPIO_ACTIVE_HIGH>` with `, <&pro_micro 18 GPIO_ACTIVE_HIGH>`, and delete the next line `, <&gpio1     07 GPIO_ACTIVE_HIGH>`.

To avoid conflict, you may compile zmk for left and right. The command is `west build -p -b nice_nano_v2 -- -DSHIELD=avalanche_left` and right for the slave. It is quite tricky in re-flashing nicenano, refer to [Flash Zmk](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20zmk#part-b-flash-zmk) for the steps suggested. 

### Common issues of Zmk
1. Refer to [Bluetooth cannot be paired and disconnect very often](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/useful%20codes%20for%20zmk%20firmware.md). 
2. Using two bluetooth devices at the same time may interrupted typing experience. 



### Future alternatives
:construction: Pom switch plate for proper 1.6mm thickness. Carbon fibre option remains in pre-order form.

:construction: Provide simple acrylic bottom and exclude 3D printed case for price markdown. 

:construction: 3D printed case remains available and with tenting legs included.

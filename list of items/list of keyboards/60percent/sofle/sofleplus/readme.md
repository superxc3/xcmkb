# Sofle PLUS


|![image](https://github.com/superxc3/xcmkb/assets/79617315/bd81dc8d-9970-4951-b874-163cdaebc7bc)|
|:--:|

Sofle PLUS is brought to you by XCMKB, a revamp of the most popular split keyboard originally designed by Josefadamcik.

## Features

###  New Hotswap Options
Enjoy the freedom to choose between MX and Low Profile Choc V1 switches for ultimate customization.

###  Enhanced Encoders
Discover more encoder options for increased functionality.
- Horizontal scroll wheel, convenient to scroll!
- [Pimoroni trackball](https://shop.pimoroni.com/products/trackball-breakout?variant=27672765038675), adds cursor control to move and scroll without moving your hand to your mouse
- [Haptic Bzzz](https://shop.pimoroni.com/products/drv2605l-linear-actuator-haptic-breakout?variant=27859486867539), programmable vibration with a range of built-in patterns will really get you buzzing!

###  Tailored for Wireless
Experience convenience with a power button for battery-saving and support for [nice!view](https://nicekeyboards.com/nice-view/), using Sharp's cutting edge Memory-in-Pixel technology, maintains 30Hz at e-paper level power draw. 
- Dedicated power button
- Low power draw nice!view supported

### Greater RP2040 MCU, Greater Firmware
Now with the more powerful RP2040 MCU! Advanced firmware supporting:
- 10 layers,
- 32 tap dance,
- 32 combos,
- 32 key overrides,
- Qmk settings enabled, 
- Full RGB lighting effects enabled in Vial.

| Feature                 | Sofle v2                          | Sofleplus                              |
|-------------------------|-----------------------------------|----------------------------------------|
| Switch Compatibility    | MX hotswap only                   | MX and Choc V1                         |
| Encoder Options         | Knob only                         | Knob, Horizontal Scroll Wheel, Pimoroni Trackball (Cursor), Haptic Bzzz (Vibration) |
| Wireless                | No dedicated power button         | Dedicated power button                |
| OLED Display            | OLED                              | OLED and Niceview Support (wireless)  |
| Firmware Features       | Limited                           | Specially tailored for end users      |
| Programmable Encoder    | No                                | Yes                                    |
| Number of Layers        | 4                                 | 10                                     |
| Tap Dance               | No                                | 32                                     |
| Combos                  | No                                | 32                                     |
| Key Overrides           | No                                | 32                                     |
| QMK Settings            | No                                | Yes                                    |


Sofle Plus retains the ProMicro footprint, allowing for a seamless Bluetooth upgrade in the future without the need for desoldering!

## What is included?
- 1 x Left and right pre-soldered Sofle
- Pre-flashed with VIAL
- 1 x TRS cable
- 2 x knobs or depends on your choice
- 2 x oleds or depends on your choice
- Switch plate, stacked acrylic case or 3D case based on your purchase

## What is not included and you need to prepare:
1. 58 3/5 pins switches mx or kailh lp choc v1 depends on your board, recommended to get extra 1-2. 
2. 58 x 1u keycaps; 1 thumbkey on each side supports up to 1.5u
3. Type c to type a cable. Type c to c not suitable for promicro.
   
# User Manual
### MX user
- For pom / carbon fibre switch plate, prepare switch puller. It is advised to remove the switch plate and insert the switches one by one rather than inserting them directly.
- For 3D printed switch plates, it is generally recommended to insert the switches directly without removing the switch plate.

### LP choc user
- No switch plate can properly lock the switch. When you remove the keycap, the switch will be pulled along with it. If the switch is locked in the switch plate, you can either wiggle the switch and pull it out, or disassemble the board and push the switch from the bottom of the PCB.

### Key Remap
Download [Vial](https://get.vial.today/download/) for key remap. No flashing is required unless you are purchasing build kit. Basically plug and play. 
![image](https://github.com/superxc3/xcmkb/assets/79617315/b52e9b8e-1c53-4f9f-836d-1c9b244849fb)

The quantum can achieve tap feature such as: Hold as Left Control; tap as Space. Just hover on it and it will explain how it works.
![image](https://user-images.githubusercontent.com/79617315/208881636-7c6481e0-e320-4ad1-b727-bb4b7e0616f4.png)

Also layer cycle through Layer tab:
![image](https://user-images.githubusercontent.com/79617315/208881348-fc678b95-c729-4dff-94a2-946d5032845c.png)

![combination](https://github.com/superxc3/xcmkb/assets/79617315/f9fdb327-4391-46f2-a700-533f6dd97be1)

You can refer to [Vial Tutorial](https://get.vial.today/manual/) for Layers, Macros, Tap Dance, Combos features (this is suitable for rp2040 promicro). 


![Trackball manual](https://github.com/superxc3/xcmkb/assets/79617315/6ba8086a-2a59-485d-ba2f-0292656fedfb)

### Notes
1. :warning: This step is crucial to prevent bricking the MCU. When connecting a split keyboard, it is important to ensure proper and correct connections. Please refer to [demo](https://www.instagram.com/tv/CdpYrWBJuD9/?igshid=YmMyMTA2M2Y=) here.
![image](https://user-images.githubusercontent.com/79617315/204213627-3c877043-aae7-45f9-804b-e50d5ad57624.png)
3. If you brick your MCU, your board will no longer function. You will need to replace the set of MCUs if the MCU is bricked.
4. :warning: For RGB per-key users, it is recommended to set the brightness to a maximum of 50% only. Setting it higher than that may result in an unstable power supply to the USB, potentially causing the keyboard to disconnect from your PC.
3. Common issues refer to [Common Issues](https://github.com/superxc3/xcmkb/blob/main/list%20of%20guide/common%20issues.md).

## Other link gates as follow:
1. [Build Guide](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/build%20guide.md)
2. [Firmware](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/firmware.md)

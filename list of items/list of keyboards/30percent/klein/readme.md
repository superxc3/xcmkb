# Klein
Klein is designed by [snsten](https://github.com/snsten/Klein), a 36 keys, columnar staggered, split keyboard named after Felix Klein.

![image](https://user-images.githubusercontent.com/79617315/224519584-8a371f3a-4560-4506-b8f7-250b502877f7.png)

## Features
### Dual MCU footprint
Thanks to the affordable Seeed Xiao BLE MCU, wireless builds can now be even more budget-friendly. The dual MCU socket design, which includes both the typical Promicro and the new Seeed footprint, provides greater flexibility in building wired and wireless mechanical keyboards. 

### Dual hotswap sockets
Additionally, the hotswap socket accommodates both MX and Choc switches, allowing for even more customization options.

## Wireless Seeed Low Profile Choc version
- Socketed Seeed XIAO BLE Wireless MCU
- 800mah lithium battery
- Hotswap LP Choc v1
- Original 3D printed case designed by author
- TRS cable included
- EC12 encoder with 3D printed knob (working on both sides)
- No switch plate (does not required due to pcb design)

## Wireless Seeed Low Profile MX version
- ditto
- EC12 encoders replace with higher profile EC11 with knob
- Polycarbonate switch plate for mx with standsoff
- Higher profile 3D printed case modified by XCMKB

## Wired USB C Promicro MX or Choc version
The Wireless Seeed Choc is the most cost efficient setup for Klein, if you are looking for wired version:
- Socketed USB C Promicro MCU
- Hotswap MX Socket or Choc socket or both
- Acrylic bottom plate
- No switch plate for Choc option
- Polycarbonate switch plate for mx version, extra standsoff and screw will be provided
- Higher profile EC11 rotary encoder with knob
- Optional 0.96 larger oled screen, default comes with Klein logo only


### What is not included and you need to prepare
Do let us know if you need help to bundle with switches and keycaps.
- 36 low profile choc v1 switches (linear: 15g pink /25g purple /35g red choc; clicky: 50g white /52g tiffany)
- 36 low profile keycaps (MBK/CFX/Kailh)
- USB C to USB A cable

### Firmware
- Default ZMK supports for Seeed XIAO BLE, fork [shield](https://github.com/snsten/Klein-zmk) written by author. Edit the keymap according to your needs, click action to download firmware.
- If your Seeed XIAO BLE was flashed, you may drop reset.settings file from firmware and drop left and right uf2 accordingly. 
- The default master is set on right side, do aware when you connect bluetooth device. 

:rotating_light: Since ZMK is designed for advanced users, we assume that you are already an expert in using it. Feel free to DM us if you encounter any problems, but please note that we may not always be able to reply.


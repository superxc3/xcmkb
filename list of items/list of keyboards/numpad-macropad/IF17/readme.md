# IF17 Numpad

![if17](https://user-images.githubusercontent.com/79617315/209417051-e1870918-284d-42f4-ab7d-f05a64b4220d.jpg)

## Key remap software VIAL
Key remap download [Vial](https://get.vial.today/download/). Always hover on the key if you are not sure the function is.

## Installation guide
1. It is not recommended to install switches directly to the switch plate without dissembling it, especially for the first time user. Two key reasons: pc switch plate flex and soft; it is gasket！
2. Unscrew the top 4 screws from the frame, and 4 screws from switch plate
3. Take out the switch plate and insert all the 17 switches one by one, place it back to pcb and install the 4 screws of the switch plate. 
4. Assemble and fasten another 4 screws on the acrylic frame. 


## Connection
For 2.4g just install the dongle. Try to toggle the power button near to usb port if it is not responding. The following explains bluetooth connection. PLEASE READ FINISH THIS SESSION BEFORE YOU CONNECT YOUR BOARD. 

|![image](https://user-images.githubusercontent.com/79617315/209416348-095caa94-79d7-4305-984d-e028b7825a1e.png)|
|:--:|
|You can remap the connection under `User`. |

1. BT_GB1 > Add bluetooth device from your pc
2. If you want to clear bluetooth pairing, you have to clear on both sides (your keyboard and pc). BT_1 > BT_RST clears your keyboard pairing; go to bluetooth device on your pc, `remove device`. Repeat step 1 to connect your device for the very first time.
3. BT1 / BT2 / BT 3 allows you to switch between different devices. 
4. It is recommended to pair only one profile to a device. For instance, do not pair BT1 and BT2 to your single pc to avoid conflict. 

|![image](https://user-images.githubusercontent.com/79617315/209416741-42fb4e94-c4e4-4314-b77b-af706cad4adc.png)|
|:--:|
| Bluetooth connection `IF17-1` indicates connected to profile `1`|

| Keycode in Vial | Function |
|:--|:--|
|BT_RST  |  Clear bluetooth pairing|
|BT1  |  Bluetooth profile 1|
|BT2  |  Bluetooth profile 2|
|BT3  |  Bluetooth profile 3|
| BT_GB1 | Bluetooth profile 1 discoverable |
|BTRF | 2.4g connection |
| SEL_OUTPUT | Connected through certain mode, default by wired |
|SYS_SLEEPTIME| Sleep time for connection, the shorter the time the lesser battery usage |
| BT_SLEEPTIME | Bluetooth sleep time |
| :name_badge: BT_FLASH | DO NOT PRESS THIS, IT CLEARS EVERYTHING AND FLASHING THE DEVICE IS LENGTHY |
| :name_badge: RF_FLASH | DO NOT PRESS THIS, IT CLEARS EVERYTHING AND FLASHING THE DEVICE IS LENGTHY |

### Default Keymap for Connection

|![combination](https://user-images.githubusercontent.com/79617315/210479982-64f73384-72d9-4751-a322-15e64861a065.jpg)|
|:--:|
| Click the knob to access layer 10 > then click . to access layer 11 > and you can find the keymap of layer 11 as follow |

|![Layer 11](https://user-images.githubusercontent.com/79617315/210478936-216e5085-4bd6-4d4e-b4d0-d12a90fbacad.JPG)|
|:--:|
| Layer 11 default keymap. Click the knob to go back Layer 10, click again to go back to Layer 0 |

|![Layer 10](https://user-images.githubusercontent.com/79617315/210478930-32dea193-86f8-4964-ba17-b83343fae24c.JPG)|
|:--:|
| Layer 10 default keymap for your reference |

## Layer
A total of 12 but please utilise the top 10th only (Layer 0 to 9). Layer 10 and 11 have set with default keymap.
![image](https://user-images.githubusercontent.com/79617315/209416316-8b4d6ae1-64df-4afd-b69c-3237454ccbfc.png)

## OLED
| ![image](https://user-images.githubusercontent.com/79617315/209416108-2a1e9d3b-1521-42bb-8e05-8faa6ec7bcc5.png)|
|:--:|
| Animated Luna Pet > Layer > Capslock > Numlock > Connection > Battery| 

Capslock and numlock indicator only reflected when it is connected. MAC will not responding to these indicators. 


## NKRO
Recommended to turn off. 

## Commonly used vial keymap
Switch between layers:
![image](https://user-images.githubusercontent.com/79617315/209417128-f588cad0-53f9-4feb-8a3a-33714a95e0e5.png)


The quantum can achieve tap feature such as: Hold as Left Control; tap as Space. Just hover on it and it will explain how it works.
![image](https://user-images.githubusercontent.com/79617315/208881636-7c6481e0-e320-4ad1-b727-bb4b7e0616f4.png)

Also layer cycle through Layer tab:
![image](https://user-images.githubusercontent.com/79617315/208881348-fc678b95-c729-4dff-94a2-946d5032845c.png)

## Firmware
:warning: This is not an open source numpad, hence no qmk codes will be shared. All settings and configuration already enabled.
![image](https://user-images.githubusercontent.com/79617315/209416330-7f92b7d6-d237-486b-8960-7f2d111514d0.png)


# ZMK Reviung41

ZMK works like wireless QMK, it does not offer real time key mapping like VIA however offers wireless feature.

ZMK setup refers to this [link](https://zmk.dev/docs/development/setup).

Our Reviung41 is flashed with the following features:
- Underglow
- NKRO
- USB Polling rate 1000

Default keymap refer [here](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/40percent/reviung41/firmware/ZMK/reviung41.keymap), full list of keycodes find [here](https://zmk.dev/docs/codes/), mod tap etc find [here](https://zmk.dev/docs/codes/modifiers).

To add a new layer, just copy one of the layer codes and duplicate, name it with a different name. 

![image](https://user-images.githubusercontent.com/79617315/154186601-09f1ef54-3b78-494b-9300-5eebc5e215a8.png)

### First time user to check for connection:
![image](https://user-images.githubusercontent.com/79617315/154940017-8fe96cb9-26b3-485a-b428-b4df0cfedea2.png)

### Common Issue

|![image](https://user-images.githubusercontent.com/79617315/155276214-3465093a-1b6e-406c-a615-fb53a1eb372d.png)|
|:--:|
| Couldnt connect the board (screenshot credited to daijoubu)|
1. You do not need to connect the board through cable during troubleshooting.
2. If you are window user> Start> Bluetooth > Select your board > Remove device
3. Select BT profile you last connected (hold fn3+bt1) > (hold fn3+bt clear)
4. If you are not sure which profile you have selected, you may need to clear it one by one as step 3 above.
5. Bt clear only clear one particular bt profile but not clear all.
6. Now reconnect it by select a bt profile.
7. Good luck!

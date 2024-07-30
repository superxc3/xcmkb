# Zazu 

![Image_20240730162923](https://github.com/user-attachments/assets/58591898-0298-4512-907c-13d13bf851d5)



The board is designed by [AlaaSaadAbdo](https://github.com/AlaaSaadAbdo/battoota/tree/main) with [QMK_Firmware](https://github.com/AlaaSaadAbdo/qmk_firmware/tree/develop/keyboards/mabroum/zazu).  We are not responsible for and will not assist with firmware configuration.
Please note that we have 4 extra units available, as we are keeping one for personal use. Once sold out, they are considered sold out.


## User manual 
1. The outer scroll ring may be slightly loose. We’ve pre-taped it for you. If it becomes loose over time, you can tape the inner part of the ring for added stability.
2. Download [VIAL](https://get.vial.today/download/) to remap the keys. Note that it is VIAL, not VIA.
3. The quantum can achieve tap feature such as: Hold as Left Control; tap as Space. Just hover on it and it will explain how it works.
<div style="text-align:center;">
    <img src="https://user-images.githubusercontent.com/79617315/208881636-7c6481e0-e320-4ad1-b727-bb4b7e0616f4.png" style="width: 100%; max-width: 100%;">
</div>

4. Also layer cycle through Layer tab:
<div style="text-align:center;">
    <img src="https://user-images.githubusercontent.com/79617315/208881348-fc678b95-c729-4dff-94a2-946d5032845c.png" style="width: 100%; max-width: 100%;">
</div>

5. Some useful one:
<div style="text-align:center;">
    <img src="https://github.com/superxc3/xcmkb/assets/79617315/f9fdb327-4391-46f2-a700-533f6dd97be1" style="width: 100%; max-width: 100%;">
</div>


### Mac users
1. LGUI/RGUI = Windows/Command/Meta
2. LALT = Option
3. RALT = Option/AltGr
4. Further please read [Keycodes Overview](https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes.md)

## Special keycodes  
Some useful one as listed below especially to assist trackball control. The rest please refers to `keymap.c` and `keys.h` for Zazu's special keycodes in QMK Firmware link above. 

1. `DPI+`
2. `DPI-`
3. `SNIP` - moves cursor super slow for precison
4. `SMTG` - snip mode toggle on and off
5. `DRAG` - hold to activate trackball scroll
6. `DMTG` - toggle scroll mode
   
## Fimrware changelog

### v1.00
1. Add `RGB Sleep` to config.h allows RGB goes to sleep when pc is sleep
2. Correct visual presentation of vial layout.
3. Correct User as previous version not working. 

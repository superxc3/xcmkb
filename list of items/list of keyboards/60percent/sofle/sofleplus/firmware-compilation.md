# Firmware compilation
This session is restricted to certain users only. Please flash at your own risk. We are not responsible for any board failure resulting from flashing.

1. This is build through [vial-qmk](https://github.com/vial-kb/vial-qmk) directory.
2. Copy the xcmkb folder to your qmk vial firmware directory. username > vial-qmk > keyboards > xcmkb > sofleplus
![image](https://github.com/superxc3/xcmkb/assets/79617315/de9f75e6-e151-44d9-8f7b-9c5918e74441)
3. Flash using qmkmsys so right trackball can be led up.
4. Remove usb c, remove trs cable, connect usb c to left/right, do it for another half.
5. Use this command for left: ```qmk flash -kb xcmkb/sofleplus/2040 -km vial-spacexc2 -bl uf2-split-left```, double press reset button on your board located on the front of pcb, in between oled and trs port.
6. Use this command for right: ```qmk flash -kb xcmkb/sofleplus/2040 -km vial-spacexc2 -bl uf2-split-right```


## List of firmware
1. Date: 20230312 [vial-spacexc2](https://drive.google.com/file/d/14DlU5cgb2wjtidxAvTpWAv2AsGakaz7k/view?usp=drive_link)

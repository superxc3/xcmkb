# Common Issues

#### Need to re-plug usb when pc restart
- remove `split-usb-detect` in config.h
- please download relevant hex files for the update above: [Avalanche v4](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/avalanche/v4/firmware.md#rev3-vial-rev3), [Sofle variation](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofle%20v1%20%26%20v2%20mx/firmware#standard-firmware-flashed-for-sofle-v2-20230405), [Corne](https://drive.google.com/drive/u/0/folders/1O1TQ90idPsqGZOqgcTjGs8TE27zHC5nr). 

#### Certain keys are not registered
- Check any bent pins on your switch. 
- Your cable might be not a data cable which can transmit data. This happens very often on micro usb cable. Try with another cable or buy a usb data cable.
- For mac book type c to c cable is not working. You have to do it for type c to type a. Heard you can flash the board with typec to c cable and it might able to make it work, yet to test.

#### Rows or columns registered together
- Check any bent pins on your switch.

#### Keys not mapping
- Launch one application each time (Via only or VIAL only), do not launch together to avoid conflict.
- VIAL can be quite buggy. 

#### Weird keyremap / some keys not function accordingly
- Try to remove oled cover and push the mcu tight. The mcu might be loose during shipping (sometimes we have violent courier). Rarely happened case but this simple trick helps to avoid shipping fee to return refund etc.

## Split Keyboards
#### Oled is up but key cannot be registered
- Make sure you push trs cable fully. 

#### Master split is working perfectly, slave side is not registering
- Make sure you push trs cable fully. 

#### Boards disconnected after several seconds of connection
- Might be overpower needed for usb. Try to lower the brightness (especially rgb per key) to 50% and lower.

`Anything just dm us, we dont bite.`



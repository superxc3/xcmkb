This is a backup session just in case. Kindly ignore this session.
## Standard Firmware (2023.07.13) for RP2040 promicro 


We use [Bastardkb/Splinky](https://github.com/Bastardkb/Splinky) or similar RP2040 Pro-Micro. 
1. Standard firmware by 2023.08.05 is Version 1.1.
2. For those who want to edit oled or so, source code is [included](https://drive.google.com/drive/folders/1-6yim1sLNgdcoQgKbDtAbBsG6yMPpH2_?usp=drive_link).

   a. Please set up [Vial Environment](https://get.vial.today/docs/porting-to-vial.html#1-prepare-your-build-environment). If you are completely new to qmk_firmware, command `qmk setup -b vial vial-kb/vial-qmk` in qmk msys to clone vial-qmk to qmk firmware in your pc.
   
   b. Copy content to your qmk-vial keymap directory.
   
   c. Edit oled code in `keymap.c`.

   d. In your QMK MSYS, compile using `qmk compile -kb crkbd -km xcvial`.

   f. Go to your `build` folder in your vial-qmk directory for uf2 file you've just compiled.

   g. Double press the physical reset button on your board and just drag the uf2 file to your both sides.

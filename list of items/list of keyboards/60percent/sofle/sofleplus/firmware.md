# Firmware of Sofle Plus

Sofle is powered by QMK-firmware (Firmware has been merged and can be found on the QMK master). The firmware here are highly customised and modified by us, they are used to flash your boards before we ship to you. Hence, list of firmware here are totally different from the default QMK VIA firmware found at the [official repo](https://qmk.fm/keyboards/). 

Sofle Plus is compatible with any Sofle v2 or v1 firmware, as well as Choc firmware, but not with firmware from Keyhive. It is specifically designed based on the RP2040 ProMicro, incorporating all functions and capabilities in Vial. 

## Standard Firmware of Sofle Plus (RP2040)
1. All wired versions of Sofle Plus come pre-flashed with this firmware.
2. The board you purchased comes pre-flashed, except for the build kit. We strongly advise against flashing it unless you are familiar with the process or have been instructed to do so by us.
3. Firmware download from [here](https://drive.google.com/drive/u/0/folders/1vNPOlv2NhzNlO9qoJ0fS3oOtKQtKS7rQ).
4. To flash the firmware, double press the reset button between the OLED and TRS jack to open an explorer window, then drop the UF2 file.
5. Standard firmware named `xcmkb_sofleplus_2040_vial-ud-p_promicro_rp2040-left/right-3` is used.

### Features
1. Auto-detected in [Vial software](https://get.vial.today/download/), supports Win, Linux, and Mac. Real-time key remap software without the needs of code compilation. No load json is required. 
2. 10 [Layers](https://get.vial.today/manual/layers.html), maximum fn! You can refer to [Miryoku](https://github.com/manna-harbour/miryoku) for inspiration.
3. 32 [Combos](https://get.vial.today/manual/combos.html), adds custom actions when a certain combination of keys is pressed.
4. 32 [Tap dance](https://get.vial.today/manual/tap-dance.html), taps and hold for different key outputs.
5. 32 Key overrides
6. QMK settings allows you to configure the fine details of how QMK operates, including tapping term, permissive hold etc. Read more on [QMK Firmware](https://docs.qmk.fm/#/).
7. Mousekey allows you to remap mouse key on keyboard, including left click, right click, scroll etc.
8. RGB Light enabled and including all RGB lighting effects.
9. Pimoroni trackball and haptic bzzz enabled. Further key configuration on `Custom` tab.
10. `Super ALT↯TAB` is enabled in `Custom` tab as `ATABF` and `ATABR`, allows you to cycle tab through window, especially suitable for knob function.


# Firmware
1. Flashing manual refer to [RP2040 Flashing guide](https://github.com/superxc3/xcmkb/blob/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus/flashingboard.md).
2. Tick `Azoteq` in the Layout. Please press `DPI0` after you flash your firmware to activate the trackpad.
3. You can load default keymap [here](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/sofleplus2_keymap.vil?v=1733494418) by File>Load Saved Layout, ignore any error and click other tab to refresh the keymap. 


# SoflePLUS2
|![Image_20240724140025](https://github.com/user-attachments/assets/7db5fc4e-b2d2-4977-9250-ff7491b30f86)|
|:--:|
|SoflePLUS2 with smaller TPS43 trackpad, USB-C connection|

## v3.00 beta 
- This project is currently in beta.
- For new pcb released in mid-dec 2024: spinning disk in v0.9, left PCB v2.09. 
- Remove `#define SPLIT_WATCHDOG_ENABLE` and `usb detect` and replace with `#define SPLIT_WATCHDOG_ENABLE` for re-plug issue
- Center click (GP12) of spinning disk remains as left click, the rest remappable in Vial, new Col6 introduced with massive change on the code.
- For Starter or Standard without RGB underglow, please download this [v3.00](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2anostandard_vial300.uf2?v=1734074204), [v3.00_65](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2anostandard_vial300-65.uf2.uf2?v=1735600548)
- For Signature or with RGB underglow and Per key, please download this [v3.00 Signature](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2ano_signature_v300.uf2?v=1734074651) and [v3.00 Signature Tps65](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2anosignature_vial300-65.uf2?v=1737582961).
- Update on 2024-12-13

## v2.05a - Master oled flickering on mac
- The master OLED flickers when the keyboard goes to sleep on macOS. Otherwise, everything works fine, including returning to normal upon wake.
- For Starter or Standard without RGB underglow, please download this [v2.05a](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2u_vialazo205a.uf2?v=1733493904)
- For Signature or with RGB underglow and Per key, please download this [v2.05ua](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo205withua.uf2?v=1733494156)
- Update on 2024-12-6

## v2.05 - RGB matrix fix 
- Realise some lighting effects dont appear properly especially on heatmap etc. Issue fixed.
- Fix default layer indicator for Layer 2, changes from yellow to the more appealing cyan.
- Add last row of thumb keys and rgb underglow as layer and capslock indicator
- For Starter or Standard without RGB underglow, please download this [v2.05](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2u_vialazo205.uf2?v=1732695672)
- For Signature or with RGB underglow and Per key, please download this [v2.05u](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo205withu.uf2?v=1732697331)
- Udate on 2024-11-27  

### Next breaking changes v2.04 - Azoteq improvements
- Beta download [here](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo204.uf2?v=1730427148)
- For large trackpad download [here](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo204L.uf2?v=1731074577)
- If your pointing device reverse direction for large trackpad, download [here](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo204LR.uf2?v=1731074561)
- Add `SCRLR`: change horizontal scroll direction
- Add `MOSCR`: hold to trigger scroll with single finger. This reduces the needs of using two fingers to trigger scroll, easier to trigger.
- Add `TOSCR`: toggle single finger scroll
- Horizontal scrolling already proved to work for previous version
- Change `ee_hand` to `master_left` to simplify the flashing process (2024.11.10)
- Looking more possibilities to enhance azoteq improvements before release (2024.11.1) <br>

#### Known issue
- USB on the right triggers an unintended right click. It works correctly with USB on the left.
- MOSCR or TOSCR vertical/horizontal scrolling inadvertently triggers horizontal/vertical scrolling, which may cause issues in Excel files. Two-finger scrolling works without any problems.

#### Looking forward
◯ Vial-gui improvements, swipe and zoom gestures

## v2.04 - RGB UP 
- Based on the v2.04 beta
- Specially for RGB per key models only, RGB layer and capslock indicator shines from top
- [Download](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo204-rgbup.uf2?v=1732152745)

## v2.03 - Classic
- ditto v2.03
- no trackpad. encoders on both sides
- [Download](https://cdn.shopify.com/s/files/1/0691/8963/2259/files/xcmkb_sofleplus2_vialazo203c.uf2?v=1731074764)

## v2.03 - 65
- ditto v2.03
- for larger trackpad 65
- [Download](https://drive.google.com/file/d/18joRFv1wW972N29pvW-bzpu7NB4XBwVa/view?usp=drive_link)

## v2.03 - Ergomech edition
- ditto v2.03
- Layer and capslock indicator changes to 5 thumb keys as RGB underglow couldnt be seen from Ergomech case
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1uCtHUZd_OpgFgbz7Knq8WT9mL4aBS1Ek/view?usp=drive_link)

## v2.03 
- Layer and capslock indicator for rgb underglow only. Using dimmer indicator color to avoid flickering.
- Able to wake from sleep
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1c0jsC7wQanfzKTrb11KxgmNjGjE4YRMC/view?usp=sharing)

## v2.02a 
- Fix issue on requiring re-plug after reboot or fresh restart by adding `#define SPLIT_WATCHDOG_ENABLE` in `config.h`.
- This is only for RGB underglow version, rgb indicator for layers and capslock remain
- This is also compatible with TPS43 trackpad, rotated.
- Add `DPI-` in `user` tab to change DPI of trackpad.
- Oled can display DPI speed now. Capslock and numlock indicator on oled is removed.
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1DG-7HxZxbw7_mIyUtNQ17sIe1OhCStHt/view?usp=drive_link)

## v2.02b - rgb indicator removed
- This is for full rgb backlighting and underglow version, rgb indicator for layers and capslock removed.
- Fix for correct visual presentation on Azoteq layout. Remove remappable dip click on the left.
- Others ditto v2.02a
- This is for PLUSv2 with usb-c comms connection only. TRS connection incompatible.
- [Download](https://drive.google.com/file/d/1CPBPp-_daynmbj_SM6n5wjifNQDMn945/view?usp=drive_link)

# SoflePLUS
|![image](https://github.com/user-attachments/assets/4bb93a8d-2606-4aae-afc8-74f1cbea852c)|
|:--:|
|SoflePLUS with large TPS62 trackpad, TRS connection|

## v1.02b - oled dpi fix
- yet to test, may not worked.
- update on 2024-09-02
- correct the visual information for oled, omit rocket space animation as we only have one oled for this version.
- oled can display DPI value, capslock indicator omitted, shows through rgb indicator instead.
- [Download](https://drive.google.com/file/d/1m-1oIWS8lbtKk6Lv-TwTBI517SpusS6L/view?usp=drive_link)

~~## v1.02a - reported not working on 20240902~~

## v1.02
- Fix issue on requiring re-plug after reboot or fresh restart by adding `#define SPLIT_WATCHDOG_ENABLE` in `config.h`.
- This is only for RGB underglow version, rgb indicator for layers and capslock remain
- This is for PLUS with trs connection only. C-C connection incompatible.
- TPS62 trackpad
- Add `DPI-` in `user` tab to change DPI of trackpad.
- No DPI display on OLED
- Compatible for normal Sofle without trackpad
- [Download](https://drive.google.com/file/d/1Rhh3cRpNw75QYf8Do9ucuipwj_ymHcOp/view?usp=drive_link)


  
# Source Code
Keep this for personal use only. 

## v2.03 
- vial-qmk environment, pulled on 2024-09-02, compiled with qmk msys 1.9.0
- [Download](https://drive.google.com/drive/folders/1OM-pccKEOvNtJggC9Q17KyIiNZYJbKfr?usp=drive_link)

## v1.02b
- vial-qmk environment, pulled on 2024-09-02, compiled with qmk msys 1.9.0
- [Download](https://drive.google.com/drive/folders/1XHns0GvEJjhrjjdFua79qMDN-CcppcxN?usp=drive_link)

## v1.02
- vial-qmk environment, pulled on 2024-09-02, compiled with qmk msys 1.9.0
- [Download](https://drive.google.com/drive/folders/1XHns0GvEJjhrjjdFua79qMDN-CcppcxN?usp=drive_link)



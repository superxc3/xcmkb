# SoflePLUS Aluminium Case Upgrade

|![08eb7809853ca20e03f912d7f384fc3](https://github.com/superxc3/xcmkb/assets/79617315/66049693-02b2-45b6-bc86-25648ea05b98)|
|:--:|
| SoflePLUS with Ergomech Aluminium Case|

SoflePLUS is a split keyboard with a 6x4+5 keys layout and OLED displays. It is based on the original [Sofle](https://github.com/josefadamcik/SofleKeyboard) design by Josef Adamcik, but with some improvements and modifications by XC, the designer of SoflePLUS. You can find more details about SoflePLUS [here](https://github.com/superxc3/xcmkb/tree/main/list%20of%20items/list%20of%20keyboards/60percent/sofle/sofleplus).

One of the features of SoflePLUS is that it can be upgraded to an aluminium case from [Ergomech](https://ergomech.com/). However, the aluminium case from Ergomech is not a direct fit for SoflePLUS. It requires some minor modifications. The good news is that no desoldering and soldering are required, and the process is relatively simple and straightforward.

In this page, I will show you how to change or upgrade the case of SoflePLUS to aluminium case from Ergomech, step by step. I will also provide some tips and tricks to make the process easier and smoother. Let's get started!


## Ergomech Aluminium Case

The suitable aluminium case for SoflePLUS is the **Enclosed Case for Sofle V2** from Ergomech. This case has a sleek and elegant design, with a chamfered edge and a cutout for the OLED displays. It also has a built-in stand that allows you to adjust the angle of the keyboard for your comfort.

The Enclosed Case for Sofle V2 is available in three colors: **black**, **white**, and **silver**. You can choose the color that matches your preference and style. The case also comes with a **plate** that holds the switches and the PCB in place. You can choose from three types of plates: **FR4**, **stainless steel**, or **brass**. The plate affects the sound and feel of the keyboard, so you can experiment with different options to find your favorite.

|![0d864016b3a3026c586b986a91ef397](https://github.com/superxc3/xcmkb/assets/79617315/6b83c428-3c31-4a85-aa19-142a7431c2f1)|
|:--:|
|[Enclosed Case for Sofle V2](https://ergomech.store/shop/enclosed-case-for-sofle-v2-case-only-40#attr=296,246,250) from Ergomech|

Do not buy the Enclosed Case for Sofle RGB for your SoflePLUS, as it will not fit properly. You can find more information about the Enclosed Case for Sofle RGB [here](https://ergomech.store/shop/enclosed-case-for-sofle-rgb-case-only-32#attr=226,224,228).



## Materials Needed to Upgrade
To change or upgrade the case of SoflePLUS to aluminium case from Ergomech, you will need the following materials:

- **Another shorter 2.54x5.0H 5p header**: You may need this to stack up the height. The aluminium case cant fit the pimoroni trackball as the trackball is protruded out. You can find a suitable header [here](https://www.aliexpress.com/item/1005004273173212.html?spm=a2g0o.productlist.main.9.35d73975mSojgR&algo_pvid=2781a940-0438-4d5f-9303-a806772dc872&aem_p4p_detail=202402050348533275289833399850000093139&algo_exp_id=2781a940-0438-4d5f-9303-a806772dc872-4&pdp_npi=4%40dis%21EUR%211.84%211.47%21%21%211.94%211.55%21%40210313e917071337337657121ec321%2112000028590982492%21sea%21DE%210%21AB&curPageLogUid=8OyeegRPgt17&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202402050348533275289833399850000093139_1). Please note that the header should have a spacing of 2.54 mm and 5 pins. You may need to check with the seller until you can find a shorter one like 5.0H.
- **Longer brass standoffs, M2x16mm**: As the trackball height is increased, you will need to replace them with longer ones that have a length of 16 mm. You can find suitable standoffs [here](https://www.aliexpress.com/item/1005003743229034.html?spm=a2g0o.productlist.main.85.320a2e5aQ1W1uv&algo_pvid=625871ea-7a39-4f6d-9d61-0eabb7ecd4bd&algo_exp_id=625871ea-7a39-4f6d-9d61-0eabb7ecd4bd-42&pdp_npi=4%40dis%21EUR%2111.47%215.96%21%21%2112.08%216.28%21%40210324a717071339354228389ed588%2112000027010967402%21sea%21DE%210%21AB&curPageLogUid=RnGXrH7c1J1z&utparam-url=scene%3Asearch%7Cquery_from%3A). They can be in hexagon or circular shape. Do buy a few like 14-17mm length to test out. 
- **Ugreen magnetic cable**: If your mcu socket are the one as in photo below, you will need ugreen magnetic cable (tested to be work) or thinner type c cable end so it can fit.
  
|![image](https://github.com/superxc3/xcmkb/assets/79617315/d51e0f9e-1286-47ee-8823-7a62c7106ace)|
|:--:|
|Socket that requires Ugreen magnetic cable|

- **Suitable TRS cable**: The plastic coiled cable that we provided proved to work.

## Important Steps to Assemble

To assemble the SoflePLUS with the aluminium case from Ergomech, you will need to follow these important steps:
|![e01803028af3b0d70a8f993463309d0](https://github.com/superxc3/xcmkb/assets/79617315/a159eaff-2742-475f-b4c8-b8d25fbe36f6)|
|:--:|
| Prepare for assemble |

1. **Pull up the trackball and the OLED**: Be careful not to damage the pins or the components when pulling them up.
2. **Change the brass standoffs**: The longer standoffs will fit the aluminium case better and provide more clearance for the components.
3. **Insert the taller header to the existing trackball header**: This will extend the height of the trackball header and allow you to connect the trackball to the PCB.
4. **OLED slight slant towards the USB port**: The OLED is slightly longer than the cutout in the case, so you will need to adjust its position to make it fit. Insert the PCB first, then slant the OLED slightly towards the USB port, so that the longer side of the OLED is closer to the port. This will make the OLED align with the cutout and avoid any interference with the case.
   
|![3b774ecf5321f78d735117b3d9e4ff3](https://github.com/superxc3/xcmkb/assets/79617315/27e21f8e-4c21-476c-9ece-56d77b77e8f6)|
|:--:|
| OLED slant towards the USB port |

Re-install the existing display cover. Done! Have fun!

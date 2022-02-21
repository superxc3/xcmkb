# Key Remap

## 1. VIA
Some keyboards are officially supported by QMK VIA, this includes Sofle, Corne, Reviung etc. They can be automatically detected once you have connected it to the pc. Full list check [here](https://qmk.fm/keyboards/).

|![image](https://user-images.githubusercontent.com/79617315/154873124-6340461c-81b5-4729-9784-42eac6e8aeab.png)|
|:--:|


### Software Downloads
Win platform [download here](https://github.com/the-via/releases/releases/download/v1.3.1/via-1.3.1-win.exe )

Other platforms [check here](https://github.com/the-via/releases/releases/tag/v1.3.1)




### Manual load json

|![image](https://user-images.githubusercontent.com/79617315/151114691-ddf1d27f-03e5-481a-8a68-3ebee69ece40.png)|
|:--:|
|1. For board which does not officially supported by QMK VIA, 'Searching for devices' will be appeared|
|![image](https://user-images.githubusercontent.com/79617315/151115099-f0ecfcd5-4caf-430f-a958-7c6f6d7ee02f.png)|
|2. Load json file by File>Import Keymap|

|Board-| Json file|
|:-|:-|
|!Exclamationumpad| [1x!Numpad(20211110).json](https://drive.google.com/file/d/1nIkr1yTWvWySqZaXR8mvZJhkzTd3gzse/view?usp=sharing)|
|Atlantis PS17 Numpad| [17(R).json](https://drive.google.com/file/d/1a7J1gHCxJdgyzfK0JylTgI1jKATKNYiH/view?usp=sharing)|
|Reviung5|[json](https://drive.google.com/file/d/1JrSSA8Qib7lLGcd4dTRIU_LEoJuPl7SZ/view?usp=sharing)|
|Treadstone48 only|[json](https://drive.google.com/file/d/1txMdJA8-L_YZK245hUbvFW9iSHybxjIP/view?usp=sharing)|


## 2. VIAL
VIAL software download [here](https://get.vial.today/download/)

VIAL has better supports for rotary encoders, scroll wheel, and sometimes even tap dance and combo etc (however needs to be enabled while flashing, it is also easily oversized). It is auto-detected and manual load json is not required. 

|![image](https://user-images.githubusercontent.com/79617315/154873060-5edc2146-2bd9-4bd3-b185-8f6a5cbcffa6.png)|
|:--:|

## 3. REMAP
Browser key remap clicks [here](https://remap-keys.app/). REMAP has a more friendly tap and hold features compare to VIA and VIAL. 
Do note that always launch one application each time to avoid conflicts. 

# ZMK Key Remap

ZMK is like a wireless version of QMK. However there is no real time keymapping for wireless version. It requires you to remap the key through coding (like QMK), compile and re-flash with new firmware with every single key you have remapped. Hence, ZMK wireless is recommended for advanced user who are familiar with own keymap on ergo board or user who determined to learn coding and remap the key through compilation. 

ZMK environment setup [here](https://zmk.dev/docs/development/setup/)

|![image](https://user-images.githubusercontent.com/79617315/154873335-a441ce0f-476c-4e77-8755-b2be604f6c53.png)|
|:--:|

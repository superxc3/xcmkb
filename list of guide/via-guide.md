# VIA Basic Knowledge

VIA download [here](https://github.com/the-via/releases/releases/tag/v1.3.1)

VIA built on top of QMK, hence can refer [here](https://docs.qmk.fm/#/keycodes) for key remap usage. Some useful one as follows:-

1. [Basic keycodes](https://docs.qmk.fm/#/keycodes?id=basic-keycodes)
2. [Layer switching](https://docs.qmk.fm/#/feature_layers?id=switching-and-toggling-layers)
3. [Modifier keys](https://docs.qmk.fm/#/feature_advanced_keycodes?id=modifier-keys) and [mod-tap](https://docs.qmk.fm/#/mod_tap)

## Layer Switching
QMK documentation click [here](https://docs.qmk.fm/#/feature_layers?id=switching-and-toggling-layers)

![image](https://user-images.githubusercontent.com/79617315/154783323-7e8b0f98-3190-427e-ad4b-50c522a32f9b.png)

| Key | Function |
|:-|:-|
|Fn1(Fn3)|hold to access layer 1; hold with Fn2 to access layer 3|
|Space Fn1|tap as space, hold to access layer 1|
|Mo(1)| hold to access layer 1|
|TG(1)| toggle layer 1 on or off|
|To(1)| turn on layer 1|

Above are some straight forward layer switching, you also can assign other key to access other layers, this requires ANYKEY.

## ANYKEY
This is under SPECIAL > Any in VIA. However, it is quite tricky to use ANYKEY, hence you can refer this [video](https://www.youtube.com/watch?v=hnvtdAOY6kU).


| Keycode |Output|
|:-|:-|
|LT(1, KC_ESC) | Hold as FN1, Tap as Esc|
|MT(mod_lctrl, kc_LGUI| Hold as Lctrl, Tap as Start Menu|
|MT(mod_lctrl, kc_CAPS| Hold as Lctrl, Tap as Capslock|

**other modifiers code such as lctrl+lshift refers to [Modifier keys](https://docs.qmk.fm/#/feature_advanced_keycodes?id=modifier-keys) and [mod-tap](https://docs.qmk.fm/#/mod_tap)


![image](https://user-images.githubusercontent.com/79617315/154783534-ef5e386f-d0e1-4516-93c6-51941ff750ee.png)

## Macro
Each keyboard supports up to 15 macros in VIA. 


| Function | Keycode |Output|
|:-|:-|:-|
|Single tap of A|{KC_A}|A|
|Typing of a word|{KC_A,KC_P,KC_P,KC_L,KC_E}|APPLE|
|Holding and single tap|{KC_LCTRL,KC_A}|LCTRL+A|
|Example of Macro 1|{KC_LCTL,KC_LALT,KC_I}, {KC_5,KC_0,KC_0,KC_ENT}|LCTRL+LALT+I, 500, ENTER|






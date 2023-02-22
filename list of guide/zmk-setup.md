# ZMK-Setup

1. Link refers to https://zmk.dev/docs/development/setup.
2. Basic github format refer [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links).
3. Full keycode check [here](https://zmk.dev/docs/codes).


## ZMK flashing
Launch cmd. `cd zmk`, `cd app`; then flash with `west build -b nice_nano_v2 -- -DSHIELD=reviung41`;
if go through pristine (compile before, encountered problem for second compilation, go with this method): `west build -p -b nice_nano_v2 -- -DSHIELD=reviung41`

```
cd zmk-ftc/app
```

```
west build -p -b nice_nano_v2 -- -DSHIELD=reviung41
``` 

``` 
west build -p -b nice_nano_v2 -- -DSHIELD=oceanwave
```
```
west build -p -b nice_nano_v2 -- -DSHIELD=avalanche_left
```
```
west build -p -b nice_nano_v2 -- -DSHIELD=avalanche_right
```
```
west build -p -b nice_nano_v2 -- -DSHIELD=corne_left
```
![image](https://user-images.githubusercontent.com/79617315/191435275-5c62c490-85c5-4b49-9dfe-d00b917d0c29.png)
|![image](https://user-images.githubusercontent.com/79617315/191435581-e7bad449-d2b1-49eb-9561-64283ad06680.png)|
|:--:|
|uf2 here C:\Users\yourname\zmk\app\build\zephyr|

```
C:\Users\chino\zmk-ftc\app\build\zephyr
```

## ZMK new repo

|![image](https://user-images.githubusercontent.com/79617315/191433668-b6eb7da9-b04f-488d-8d3e-25307a5003f0.png)|
|:--:|
|a. download Code| 

<p align="center">  <img src="https://user-images.githubusercontent.com/79617315/191433760-7bf40c4c-24f9-4ddf-8b54-44c94cb7c683.png">
</p>
<p align="center">
b. extract zip file to here
</p>


|![image](https://user-images.githubusercontent.com/79617315/191434554-2b2ccd27-0f2e-43df-b7d9-d2efc60c9c71.png)|
|:--:|
|c. go to cmd, `cd zmk-encoder`, `west init -l app/`, `west update`|


|![image](https://user-images.githubusercontent.com/79617315/191434710-85b73b0d-eed1-42f6-b433-94a6acffb4d8.png)|
|:--:|
|d. it takes a bit time for this process, a long process until here |


## Sensor binder for encoder
https://github.com/nickconway/zmk/blob/configurable-sensor-bindings/docs/docs/behaviors/sensor-rotate.md

Note: zmk encoder mouse scroll wheel cant work; cant find the keycode for scrollwheel.

Next step: try to merge both zmk-ftc and sensor binder for encoder

## Mouse enable for zmk-ftc (not applicable for encoder)
Mouse repo [here](https://github.com/ftc/zmk/tree/mouse-ftc); mouse codes refer [here](https://github.com/ftc/zmk/blob/mouse-ftc/docs/docs/behaviors/mouse-emulation.md)

```
&mkp LCLK
```

# ZMK Macro

Original macro guide in zmk refer [Macro Behavior](https://zmk.dev/docs/behaviors/macros)
Example of macro in `.keymap`, if you are using only single tap without any capital or shift, can just directly place `&kp`. The following macro is the example of `c89$`. But if you have other macro that requires press and release, then every macro key shall define `&macro_tap &kp C`.

```
/ {
    macros {
		spswrd: spswrd {
        compatible = "zmk,behavior-macro";
        label = "ZM_spswrd";
        #binding-cells = <0>;
        wait-ms = <10>;
        tap-ms = <10>;
        bindings = <&kp C &kp N8 &kp N9 &kp DOLLAR>;
        };
    };
};
```

Else, you may need to define each shift up and down as follow. The following macro is the example of `Xc89$`.
```
/ {
    macros {
		spswrd: spswrd {
        compatible = "zmk,behavior-macro";
        label = "ZM_spswrd";
        #binding-cells = <0>;
        wait-ms = <10>;
        tap-ms = <10>;
        bindings = <&macro_press &kp LSHFT &macro_tap &kp x &macro_release &kp LSHFT &macro_tap &kp C &kp N8 &kp N9 &kp DOLLAR>;
        };
    };
};
```

After define macro in your keymap, simply put in `&spswrd` as defined above.

## Mod-tap interrupt in ZMK
The tap-preferred flavor is similar to IGNORE_MOD_TAP_INTERRUPT. Full list on the tap behaviour see [Hold-Tap Behavior](https://zmk.dev/docs/behaviors/hold-tap#tapping-term-ms)

```
#include <behaviors.dtsi>
#include <dt-bindings/zmk/keys.h>

/ {
    behaviors {
        hm: homerow_mods {
            compatible = "zmk,behavior-hold-tap";
            label = "HOMEROW_MODS";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick-tap-ms = <0>;
            flavor = "tap-preferred";
            bindings = <&kp>, <&kp>;
        };
    };

    keymap {
        compatible = "zmk,keymap";
        default_layer {
            bindings = <
                &hm LCTRL A &hm LGUI S &hm LALT D &hm LSHIFT F
            >;
        };
    };
};
```

and for the keycode use this `&mt LALT A` 





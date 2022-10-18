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

Example of macro in `.keymap`
```
/ {
    macros {
		spswrd: spswrd {
        compatible = "zmk,behavior-macro";
        label = "ZM_spswrd";
        #binding-cells = <0>;
        wait-ms = <10>;
        tap-ms = <10>;
        bindings = <&macro_press &kp LSHFT &kp X &macro_release &kp LSHFT &kp C &kp N8 &kp N9 &kp N1 &kp N1 &kp N0 &kp N3 &kp DOLLAR>;
        };
    };
};
```

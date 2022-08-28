# ZMK-Setup

1. Link refers to https://zmk.dev/docs/development/setup
2. 
west build -b nice_nano_v2 -- -DSHIELD=reviung41

_go with pristine_
west build -p -b nice_nano_v2 -- -DSHIELD=reviung41
3. uf2 here C:\Users\yourname\zmk\app\build\zephyr

4. If we create new zmk like zmk-ftc, i download the zmk from github, copy to my pc folder. then cd zmk-ftc, west init -l app/, west update

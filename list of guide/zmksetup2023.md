Date: 20230716

# ZMK Environment Setup

1. Start from Toolchain Setup, this guide will show you how to set up a development environment for building ZMK locally. 
2. Install dependencies> Install Chocolatey

## Chocolatey for windows
a. Start> PowerShell > right click > run as administrator

b. Follow the instruction here [Install Chocolatey for Individual Use](https://chocolatey.org/install#individual).

![image](https://github.com/superxc3/xcmkb/assets/79617315/0e875dc9-1632-4ac8-a164-6b1eb1e04415)

c. After above, run the command 
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
d. Then `choco -?`.

## Choco in CMD
a. Refer to [here](https://docs.zephyrproject.org/3.2.0/develop/getting_started/index.html).

b. cmd > run as admin

c. copy `choco feature enable -n allowGlobalConfirmation`

d. and then 
```
choco install cmake --installargs 'ADD_CMAKE_TO_PATH=System'
choco install ninja gperf python git dtc-msys2 wget unzip
```


e. Close the window and open a new cmd.exe window as a regular user to continue.

## Get Zephyr and install Python dependencies
Follow [Get Zephyr and install Python dependencies](https://docs.zephyrproject.org/3.2.0/develop/getting_started/index.html).

a. as 'e' above

b. `python -m venv zephyrproject\.venv`

c. Copy below and wait. Lastly press enter again when `west update` shows as the last line.
```
west init zephyrproject
cd zephyrproject
west update
```

d. `west zephyr-export`

e. `pip install -r %HOMEPATH%\zephyrproject\zephyr\scripts\requirements.txt`

## Install Zephyr SDK
f. Close and launch new cmd

g. Paste the following
```
cd %HOMEPATH%
wget https://github.com/zephyrproject-rtos/sdk-ng/releases/download/v0.15.0/zephyr-sdk-0.15.0_windows-x86_64.zip
```

h. And again `unzip zephyr-sdk-0.15.0_windows-x86_64.zip`.

i. Paste again
```
cd zephyr-sdk-0.15.0
setup.cmd
```

## Build the Blinky Sample
a. 



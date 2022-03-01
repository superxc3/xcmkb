# Useful Codes for QMK Firmware

## Setting up QMK Environment & push to github
1. https://docs.qmk.fm/#/newbs_getting_started
2. When QMK SETUP, make sure you fork QMK_FIRMWARE in github first!
3. QMK FIRMWARE GITHUB https://github.com/qmk/qmk_firmware
4. Fork
5. qmk setup <github_username>/qmk_firmware

|![image](https://user-images.githubusercontent.com/79617315/156263094-8f47d615-f63e-4930-85e6-6b13e366a2d5.png)|
|:--:|
|qmk setup superxc3/qmk_firmware; successfully cloned from github to local|

## Gitclone to local (vial-qmk eg)
> git clone --recurse-submodules https://github.com/superxc3/vial-qmk.git

## Update Master Branch regularly
https://docs.qmk.fm/#/newbs_git_using_your_master_branch?id=updating-your-master-branch

 > cd qmk_firmware
 > 
 > git remote -v
 
![image](https://user-images.githubusercontent.com/79617315/156263488-c43c2600-6abf-41ef-8c17-2968902f718f.png)


## Personal token
> https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
> 
> log in with your username when prompt to key in
> 
> paste the token you generated earlier in qmk msys

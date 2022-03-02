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

> git clone --recurse-submodules https://github.com/superxc3/zmk.git

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

## ⚠ Git has unstashed/uncommitted changes.
> cd qmk_firmware
> 
> git status
> 
> git add .
> 
> git commit -m "adding my keymap"

![image](https://user-images.githubusercontent.com/79617315/156268287-45eb39a9-5243-4c56-8974-9da376a96d0e.png)

> git push

![image](https://user-images.githubusercontent.com/79617315/156268371-0da625ac-73a1-4f1b-a97b-1774786efec6.png)

> git push --set-upstream origin master

> git push --set-upstream --force origin master

> iex ((New-Object System.Net.WebClient).DownloadString('https://zmk.dev/setup.ps1'))


## ZMK action github
1. Create new zmk-config in github https://zmk.dev/docs/user-setup/#github-repo

> git init
> 
> git add README.md
> 
> git commit -m "first commit"
> 
> git branch -M main
> 
> git remote add origin https://github.com/superxc3/zmk-config.git
> 
> git push -u origin main

3. CMD > powershell
4. iex ((New-Object System.Net.WebClient).DownloadString('https://zmk.dev/setup.ps1'))
5. MCU and shield selection
6. Insert your github username (to make sure it push to github for action)

![image](https://user-images.githubusercontent.com/79617315/156279207-8d3812c1-6fde-43b2-a3d9-fc532feecd48.png)

Hence;

1. cmd
2. powershell
3. iex ((New-Object System.Net.WebClient).DownloadString('https://zmk.dev/setup.ps1'))
4. skip github repo to push
5. successfully created relevant files
6. cd zmk-config
7. git push --set-upstream --force origin master
8. force push to github in step7


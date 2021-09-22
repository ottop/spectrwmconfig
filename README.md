# SpectrWM configuration

## SpectrWM Configuration Files

To use the .spectrwm files, modify the configuration as you wish and put the files in your home directory to use the configuration. 

## Getting the dmenu to work like this

In my case, I used j4-dmenu-desktop (found here: https://github.com/enkore/j4-dmenu-desktop) and modified the Main.hh file slightly as it would not match my configs otherwise. The change is as follows:
1. In the Main.hh file, locate the Main() function.
2. Change the dmenu command in it to: 
 ```dmenu_command("dmenu -i -fn liberation-mono:size=10:medium -nb rgb:29/29/29 -nf rgb:c0/c0/c0 -sb rgb:19/19/19 -sf rgb:c0/c0/c0"), terminal("xterm")```
4. Compile j4-dmenu-desktop as normal

## Example screenshots

![spectrwm](https://user-images.githubusercontent.com/60475104/134374766-ae58023d-1186-4aa6-bed8-7acf3d778e33.png)

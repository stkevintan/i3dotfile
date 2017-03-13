# i3 DotFile
---

My i3 WM config files. including `compton`, `i3` and `i3blocks`.   

## Usage
```bash
git clone https://github.com/stkevintan/i3dotfile  ~/.config/i3
```
Basic Dependencies :
```yaml
i3blocks:
  wifi:
    - nmcli(NetworkManager)
  temperature:
    - sensors
  bluetooth:
    - bluez
  brightness:
    - xorg-xbacklight
i3:
  - i3blocks
  - compton
  - dmenu
  - i3-quickswitch
  - rofi
  - xfce4-appfinder
  - nitrogen

DM:
  - lightdm
  - lightdm-gtk-greeter
  - light-locker
 
clipboard:
  - clipit
```

## Snapshots

![desktop1](https://ols1thqnl.qnssl.com/2017-02-22-202712_1920x1080_scrot.png)  
![desktop2](https://ols1thqnl.qnssl.com/2017-02-22-202823_1920x1080_scrot.png)
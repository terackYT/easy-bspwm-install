# BSPWM INSTALL

easy (or not really) bspwm installation script

was made for personal use but you can use it too if you really want

this script assumes that you already have basic knowledge of bspwm and is designed to make the job quicker, not easier

## what this script does?

installs: bspwm sxhkd polybar rofi dunst nitrogen alacritty thunar bluez bluez-utils blueman pipewire-alsa pipewire-pulse pavucontrol

configures: sxhkd, polybar, bspwm, dunst

enables: bluetooth.service

(optional) installs: ly, enables: ly.service

## installation

> dependencies:
> xorg git

1. `git clone https://github.com/terackYT/easy-bspwm-install`  (clones the repo)
2. `cd easy-bspwm-install/`  (cd into repo)
3. `chmod +x install.sh`  (give install script permission to execute)
4. `./install.sh`  (start the script)

## controls

`ctrl + alt + t` to open the terminal

`super + e` to open thunar (file manager)

`alt + f4` to close the window

`super + w` to open rofi

`alt + tab` to switch between windows

you can view and edit keybinds in `~/.config/sxhkd/sxhkdrc`
check sxhkd documentation to know how to add new keybinds


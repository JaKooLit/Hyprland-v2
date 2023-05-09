
<br>
<h3 align = "center"> Arch Hyprland Dotfiles and Script Installer</h3>
<br>

## Components:

- Main Component:[`Hyprland`](https://github.com/hyprwm/Hyprland)
- Terminal: [`Foot`](https://github.com/r-c-f/foot)
- Status bar: [`Waybar`](https://github.com/Alexays/Waybar)
- Menu : [`Wofi`](https://hg.sr.ht/~scoopta/wofi)
- FIle Manager: [`Thunar`](https://docs.xfce.org/xfce/thunar/start) (Optional)

## Miscellaneous (Optional):

- Themes: `Catppuccin Mocha`
- Cursor theme: `Catppuccin Cursors`

## Needed packages:

(all of the above components) plus
`swaybg` - for wallpaper

`swwww` - for wallpaper animation

`swayidle` - not necessary but you can install

`swaylock-effects` - or swaylock

`wlroots` `wlogout` `cava` `polkit-gnome`

`mako` - for notifications

`grim` `slurp` `wl-clipboard` - for screenshot

`brightnessctl`  - for monitor and keyboard brightness - not needed for desktop

`mpv` - for wofi beats to work

`viewnior` or `swayimg`  

`pamixer` - for volume control notification. 

`playerctl` - Keyboard hotkeys multimedia controls

`xorg-xwayland` - needed to run some non-wayland app especially games

`fonts` - required awesome fonts. AUR and official repo have... else most of the waybar modules wont work. Most of configs here I used Fantasque Sans Mono. I used Cascadia Code Semibold Italic on foot.

`pipewire` - needed pipewire pipewire-pulse pipewire-alsa

`xdg-user-dirs` - by default archinstall script does not install this on "minimal" profile. That is why I have added in script


## ✨ Arch Linux quick Installation:

A guide to install :[`Youtube Link`](https://youtu.be/BUgzNdxOaD4)

a.) You can install one by one packages or choose the automatic installer script.

clone this repo by using git

cd Hyprland-v2

chmod +× install-sh

./install-sh

b.) If you want to add or edit packages, edit install-hyprland script. Ensure packages are present on AUR or official else the script will fail.

c.) Installation of Asus-ROG-utilities are entirely optional. This is only for Asus Laptop. if you select no, will skip the step.
 

## ✨ NVIDIA-Hyprland notes:
- kindly note, on configs I added all the nvidia variables from Hyprland wiki [`Link`](https://wiki.hyprland.org/Nvidia/) but by default they are not enabled. I've had issues like OBS not recording, or intermittent crashing etc, on my laptop. Check the ~/.config/hypr/configs/exec.conf and uncomment one by one to try. You can read through Hyprland-Wiki for some guidance.

## ✨ Manual Installation and Notes: 
#### you can copy, create, change, however, would appreciate to submit like a pull request or issues if you have a better solution / changes so we will all improve :)


Please note, Only provided are configs. Any Hyprland-related issues to be reported on Hyprland Github

a.) Copy / Move files / folders in your ~/.config

b.) if you have azerty keyboard [`this`](https://github.com/swaywm/sway/issues/1460?fbclid=IwAR1C8VcY_wWbGhXvT-5ApjJCQuJoJzhOVor6o5fdn0Nj1c6bD9JXoQAPQIg) might help


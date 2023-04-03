# hyprland
collection of dot config files for hyprland with a simple install script for a fresh Arch linux with paru


## Install `base-devel` package

## Clone repository
```
git clone https://github.com/vapenyk/hyprland-dots.git
```

## Install paru
```
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
```

## 1) You can grab the config files and install packages by hand with this commnad
```
paru -S hyprland-bin kitty waybar-hyprland \
    swaybg swaylock-effects wofi wlogout mako thunar \
    ttf-jetbrains-mono-nerd noto-fonts-emoji \
    polkit-gnome python-requests starship \
    swappy grim slurp pamixer brightnessctl gvfs \
    bluez bluez-utils lxappearance xfce4-settings \
    dracula-gtk-theme dracula-icons-git xdg-desktop-portal-hyprland-git
```

## 2) Or you can use the attached script `set-hypr` to install everything for you.

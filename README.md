# i3-feuf

Based on https://github.com/endeavouros-team/endeavouros-i3wm-setup.
This config it meant to be installed on arch, using stow as the dotfiles manager.

## Dependencies :

Important

- i3-wm
- rofi
- kitty
- polybar
- nautilus
- brightnessctl
- picom
- autotiling
- dex
- nitrogen
- dunst
- nm-applet
- ttf-cascadia-code-nerd

Optional

- x11-emoji-picker
- flameshot
- xfce4-popup-clipman
- arandr
- cbatticon

Install base packages :

```
yay -S stow i3-wm ttf-cascadia-code-nerd rofi kitty polybar nautilus brightnessctl picom autotiling dex nitrogen dunst nm-applet
```

(Install optional ones if you want :)

```
yay -S x11-emoji-picker flameshot xfce4-popup-clipman arandr cbatticon
```

Clone and apply the config :

```
git clone https://github.com/feufinprogress/i3-feuf.git ~/i3-feuf
cd i3-feuf
mv ~/.config/i3/config ~/.config/i3/config.bak
stow .
```

# Dotfiles

My Dots For The Catppuccin Color Scheme
Tested with fresh Arch Linux install (This guide is really for me because I forget things whenever I reinstall arch)

## All The Things Used

- [Fish Shell](https://fishshell.com/)
- [Btop](https://github.com/aristocratos/btop)
- [Neofetch](https://github.com/dylanaraps/neofetch)
- [Spicetify](https://spicetify.app/)
- [OpenAsar](https://openasar.dev/)
- [Kitty](https://sw.kovidgoyal.net/kitty/)
- [Polybar](https://github.com/polybar/polybar)
- [Picom Animations](https://github.com/dccsillag/picom)
- [Rofi](https://github.com/davatorium/rofi)
- [OhMyFish](https://github.com/oh-my-fish/oh-my-fish)
- [stalonetray](https://github.com/kolbusa/stalonetray)

## Installation

Warning!!! This guide is only for Arch based distributions and for a 1920x1080 monitor)

Installation Guide for Configs
(Will Make a Script Soon (Would be nice if someone can help make a script))

```bash
  yay -S spicetify-cli btop fish neofetch kitty polybar rofi picom-pijulius-git stalonetray polybar-spotify-module lxappearance-gtk3 nitrogen nautilus xdo spotify discord-canary dunst
  git clone https://github.com/Dueel/dotfiles.git -b catppuccin-bspwm
  cd dotfiles
  mv ~/.config/polybar/ ~/.config/polybar.old/
  mv ~/.config/rofi/ ~/.config/rofi.old/
  mv ~/.config/bspwm/ ~/.config/bspwm.old/
  mv ~/.config/sxhkd/ ~/.config/sxhkd.old/
  mv ~/.config/neofetch/ ~/.config/neofetch.old/
  mv ~/.config/kitty/ ~/.config/kitty.old/
  cp -r .config/* ~/.config/
  cp -r .local/* ~/.local/
  cp -r .stalonetrayrc /home/$USER/
```
Installation Guide for Fish Shell and Theme
- Follow the "Installation Guide for Configs" then do this:

```bash
  chsh -s $(which fish)
  curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish
```
- Then run:
```bash
  omf install lambda
```
Installation Guide for GTK Theme
  - Install The Macchiato Theme Following This [guide](https://github.com/catppuccin/gtk)
  - Then Open lxappearance and set the theme there

Installation Guide for Discord Theme
  - Have Discord Installed (I should not have to say this lol)
  - Install OpenAsar using [this](https://openasar.dev/)

- Installing the Theme
  - Copy [this](https://raw.githubusercontent.com/catppuccin/discord/main/themes/macchiato.theme.css)
  - Go to user settings
  - Scroll all they way down till you see this
  - ![Screenshot](https://i.imgur.com/ugUnL9R.png)
  - Click on it and select "Theming" and paste the .css code there

Installation Guide for Spicetify theme
  - Install The Macchiato Theme Following This [guide](https://github.com/catppuccin/spicetify)

Now Just Restart And It Should All Work!
## Screenshots

![App Screenshot](https://i.imgur.com/UfYAV4D.png)


## Acknowledgements
- [Catppuccin](https://github.com/catppuccin/catppuccin)
    - Everything was came from and based from this
- [Polybar Themes](https://github.com/adi1090x/polybar-themes/)
    - Polybar came from this
- [Rofi](https://github.com/adi1090x/rofi/)
    - Rofi things came from this
- [Neofetch Themes](https://github.com/chick2d/neofetch-themes/)
    - Neofetch Theme

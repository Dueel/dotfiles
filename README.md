# Dotfiles

My dotfiles for bspwm based on the Gruvbox color scheme

This is very unfinshed btw

## All The Things Used

- [Fish Shell](https://fishshell.com/)
- [Btop](https://github.com/aristocratos/btop)
- [Neofetch](https://github.com/dylanaraps/neofetch)
- [Spicetify](https://spicetify.app/)
- [OpenAsar](https://openasar.dev/)
- [Kitty](https://sw.kovidgoyal.net/kitty/)
- [Polybar](https://github.com/polybar/polybar)
- [Picom pijulius fork](https://github.com/pijulius/picom)
- [Rofi](https://github.com/davatorium/rofi)
- [OhMyFish](https://github.com/oh-my-fish/oh-my-fish)
- [stalonetray](https://github.com/kolbusa/stalonetray)

## Installation

Warning!!! This guide is only for Arch based distributions and for a 1920x1080 monitor)

Installation Guide for Configs


```bash
  yay -S spicetify-cli btop fish neofetch kitty polybar rofi picom stalonetray polybar-spotify-module lxappearance
  git clone https://github.com/Dueel/dotfiles.git
  cd dotfiles
  cp -r .config/* ~/.config/
  cp -r .local/* ~/.local/
  cp -r .themes/* ~/.themes/
  cp -r .stalonetrayrc /home/$USER/
```
Installation Guide for Fish Shell and Theme
- Follow the "Installation Guide for Configs" then do this:

```bash
  chsh -s $(which fish)
  curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish
  omf install lambda
```

Installation Guide for Discord Theme
- Have Discord Installed (I should not have to say this lol)
- Install OpenAsar using [this](https://openasar.dev/)

- Installing the Theme
  - Copy the code in the .css folder
  - Go to user settings
  - Scroll all they way down till you see this
  - ![Screenshot](https://i.imgur.com/ugUnL9R.png)
  - Click on it and select "Theming" and paste the .css code there
  - (If you are better at Discord Theming and want to fix up some things send a pull request it would be very helpful)

Installation Guide for Spicetify theme

- Follow this [guide](https://spicetify.app/docs/advanced-usage/installation#aur)
- Once installed run in terminal
     ```bash
     spicetify config current_theme Gruvtify
     spicetify config color_scheme gruvbox
     spicetify restore apply
     ```

Installation Guide for Polybar/Rofi

- This Polybar theme modifed very little is from the forest theme in [this](https://github.com/adi1090x/polybar-themes/)

- Installing the Bar
    - Follow the "Installation Guide for Configs"

- Launching the bar
    - Go to ~/.config/polybar/ and run the launch.sh located inside the folder

- Installing Rofi Launcher
    - Follow the "Installation Guide for Configs"
    - And thats it (If you are using my bad sxhkdrc then use Super + A to open the launcher)

Installation Guide for the GTK theme
  - Open lxappearance and set the theme there

## Screenshots

![App Screenshot](https://i.imgur.com/UfYAV4D.png)


## Acknowledgements

- [gruvbox-discord](https://github.com/iamdevnitesh/gruvbox-discord)
    - This theme was modifed and placed into here
- [Spicetify Sleek Theme](https://github.com/spicetify/spicetify-themes/tree/master/Sleek)
    - Gruvbox Spotify Theme was based on this
- [Polybar Themes](https://github.com/adi1090x/polybar-themes/)
    - Polybar came from this
- [Rofi](https://github.com/adi1090x/rofi/)
    - Rofi things came from this
- [Picom and stalonetray configs](https://github.com/beyond9thousand/dotfiles)
    - The Picom and stalonetray configs came from here
- [Neofetch Themes](https://github.com/chick2d/neofetch-themes/)
    - Neofetch Theme

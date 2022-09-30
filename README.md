# Dotfiles

My dotfiles for bspwm based on the Gruvbox color scheme

This is very unfinshed btw

## Dependencies

- [Fish Shell](https://fishshell.com/)
- [Btop](https://github.com/aristocratos/btop)
- [Neofetch](https://github.com/dylanaraps/neofetch)
- [Spicetify](https://spicetify.app/)
- [OpenAsar](https://openasar.dev/)
- [Kitty](https://sw.kovidgoyal.net/kitty/)
- [Polybar](https://github.com/polybar/polybar)

## Installation

Warning!!! This guide is only for Arch based distributions

Installation Guide for Configs


```bash
  yay -S spicetify-cli btop fish neofetch kitty polybar rofi
  git clone https://github.com/Dueel/.dotfiles.git
  cd .dotfiles
  cp -r .config/* ~/.config/
```
Installation Guide for Discord Theme

- Install OpenAsar using [this](https://openasar.dev/)

- Installing the Theme
  - Copy the code in the .css folder
  - Go to user settings
  - Scroll all they way down till you see this
  - ![Screenshot](https://i.imgur.com/ugUnL9R.png)
  - Click on it and select "Theming" and paste the .css code there

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

## Screenshots

![App Screenshot](https://i.imgur.com/G0kZRd1.png)


## Acknowledgements

 - [gruvbox-discord](https://github.com/iamdevnitesh/gruvbox-discord)
    - This theme was modifed and placed into here
 - [Spicetify Sleek Theme](https://github.com/spicetify/spicetify-themes/tree/master/Sleek)
    - Gruvbox Spotify Theme was based on this
- [Polybar Themes](https://github.com/adi1090x/polybar-themes/)
    - Theme came from this
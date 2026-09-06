# Gruvbox windows terminal config
My personal windows terminal config covering some choices of color scheme/theme.

## Requirements
- Jetbrains mono nerd font: The font used in this config.

## How to use the config
### Install jetbrains mono nerd font
Install it from this repo:
>https://github.com/ryanoasis/nerd-fonts/releases

### Replace your config
Locate your terminal **settings.json**
1. Use the shortcut **ctrl+,** in the terminal.
2. Click the button **Open JSON file**.
3. Rewrite your current json config with the one in this repo.

Note: You might need to restart the terminal, idk tho.

## Explanation
### About Ubuntu and Kali
I use wsl specifically Ubuntu and Kali, hence why there are keybinds and profiles of it. If you dont use either of those, feel free to remove them.

### Why are there so few profiles?
I mainly use either wsl or powershell, and powershell is way better than cmd, so there is no reason to include cmd as one of my profile. For azure, its literally just a link to their site, why would i include that in my profile?

### So many color schemes
I set up a few color schemes in this config which are:
1. Ayu
2. Catppuccin Mocha
3. Dracula
4. Gruvbox (Dark)
5. Kanagawa Bones

I set Gruvbox as the default color scheme since that's what i use, but you can set others as the default by modifying:
>profiles.defaults.colorScheme

### Keybinds
1. **ctrl+shift+u**: Opens up an Ubuntu tab.
1. **ctrl+shift+k**: Opens up a Kali linux tab.
1. **ctrl+c**: Copy text (the default is **ctrl+shift+c** but you can still use it).
1. **ctrl+v**: Paste text (the default is **ctrl+shift+v** but you can still use it).
1. **ctrl+shift+f**: Search text (similar to **ctrl+f** in most browsers).

## References
Color scheme hex values sourced from [Windows Terminal Themes](https://windowsterminalthemes.dev/)
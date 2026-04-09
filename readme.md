<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/repo-banners/cybr-micro-banner.png" height=200px/>

# Showcase
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-micro.png"/>
<p align="center">
  <em>micro ↗ (top-left to bottom-right: rust, python, css; bash, c++, html)</em>
</p>

# Steps
## 0. Before you start
- Make sure [Geist Mono Nerd Font](https://www.nerdfonts.com/font-downloads) is installed, you can do that from terminal with:
```bash
curl -L https://github.com/ryanoasis/nerd-fonts/releases/latest/download/GeistMono.zip -o GeistMono.zip
mkdir -p ~/.local/share/fonts
unzip GeistMono.zip -d ~/.local/share/fonts/GeistMono
fc-cache -fv
```
- Make sure micro is installed: `sudo pacman -S micro`
- See [Installation Guide](https://github.com/cybrcore/cybrdots/blob/main/INSTALL.md) if you're coming from [cybr-hyprland](https://github.com/cybrcore/cybr-hyprland) and haven't set up prerequisites yet
- [micro Github](https://github.com/zyedidia/micro)

## 1. Create theme folder and file
```sh
mkdir -p ~/.config/micro/colorschemes
$EDITOR ~/.config/micro/colorschemes/cybrcore.micro
```
## 2. Insert [cybrcore theme](../micro/cybrcore.micro)
## 3. Apply theme
```sh
micro
# press CTRL+E
set colorscheme cybrcore.micro
```

- **Window Manager** • [Hyprland](https://github.com/hyprwm/Hyprland)🎨 Tiles
  Everywhere!
- **Shell** • [Fish](https://github.com/fish-shell/fish-shell) 🐚 con
  [starship](https://github.com/starship/starship) Cross Shell Platform!
- **Terminal** • [Kitty](https://github.com/kovidgoyal/kitty) 💻 The fast,
  feature-rich, cross-platform, GPU based terminal
- **Panel** • [Waybar](https://aur.archlinux.org/packages/waybar-hyprland-git)🍧
  Patched waybar following hyprland faq!
- **Notify Daemon** • [Dunst](https://github.com/dunst-project/dunst) 🍃
  Minimalist and functional!
- **Launcher** • [Rofi](https://github.com/davatorium/rofi) 🚀 Realmente rápido
  y customizable!
- **File Manager** • [Ranger](https://github.com/ranger/ranger)🔖 custom!
- **GUI Basic-IDE** • [NvChad-V2](https://github.com/linuxmobile/nvchad-v2) Rice
  IDE!

## 🌸 Setup

<img align="center" src="/assets/r-unixporn.webp">

### Install steps (Take care about it. Isn't a tutorial)

```sh
## Install packages
./install.sh
```

```sh
## sync
./sync_config.sh
```

<details>

[Read Spanish Detailed Guide Here](https://aprendiendoaprogramar.netlify.app/configurando-hyprland-y-wayland/)

<summary><b>LONG READ DISCLAIMER</b></summary>

## INSTALLATION (Arch Based Only)

##### First of all, this is a cute disclaimer. All of this settings are installed in Artix and in wayland only! I don't know how it work in other distro.

<div align="left">

<details>
<summary><h3>Hyprland Stuff</h3></summary>

###### To get started, let's make sure we have all the necessary prerequisites. In this case, I'm using Yay as the AUR helper, but keep in mind that your system may require a different approach.

- Installation using Yay

```sh
## Hyprland Stuff
yay -S hyprland-git hyprpicker-git waybar-git \
dunst nwg-look wf-recorder wlogout wlsunset
```

</details>

<details>
<summary><h3>Dependencies</h3></summary>

- Installation using yay

```sh
## Dependencies
yay -S colord ffmpegthumbnailer gnome-keyring grimblast-git gtk-engine-murrine \
imagemagick kvantum pamixer playerctl polkit-kde-agent qt5-quickcontrols        \
qt5-quickcontrols2 qt5-wayland qt6-wayland swaybg ttf-font-awesome tumbler     \
ttf-jetbrains-mono ttf-icomoon-feather xdg-desktop-portal-hyprland-git xdotool  \
xwaylandvideobridge-cursor-mode-2-git cliphist qt5-imageformats qt5ct
```

</details>

<details>
<summary><h3>Apps & More</h3></summary>

```sh
## CLI & Tools
yay -S btop cava neofetch noise-suppression-for-voice   \
rofi-lbonn-wayland-git rofi-emoji starship zsh viewnior ocs-url
```

```sh
## Browser & File Explorer
yay -S brave-bin file-roller noto-fonts noto-fonts-cjk  \
noto-fonts-emoji thunar thunar-archive-plugin
```

```sh
# VSCode
yay -S code code-features code-marketplace
```

```sh
# Theme Based
yay -S catppuccin-gtk-theme-macchiato catppuccin-gtk-theme-mocha papirus-icon-theme sddm-git swaylock-effects-git kvantum kvantum-theme-catppuccin-git
```

```sh
# Pipewire & OBS
yay -S obs-studio-rc ffmpeg-obs cef-minimal-obs-rc-bin   \
pipewire pipewire-alsa pipewire-audio pipewire-pulse      \
pipewire-jack wireplumber gst-plugin-pipewire pavucontrol
```

</details>

</div>

<div align="left">

<details>
<summary><h3>DOTFILES</h3></summary>

###### To get started, let's make sure we have all the necessary prerequisites. In this case, I'm using Yay as the AUR helper, but keep in mind that your system may require a different approach.

```sh
git clone https://github.com/linuxmobile/hyprland-dots $HOME/Downloads/hyprland-dots/
cd $HOME/Downloads/hyprland-dots/
rsync -avxHAXP --exclude '.git*' .* ~/
```

</details>
</div>

## Credits

_Beauty community: [r/unixporn](https://www.reddit.com/r/unixporn)._

**©** _Artist who make Wallpapers, graphics and more_

**©** _All of mantainers of this amazing and opensource tools :3_

---

© [linuxmobile](https://github.com/linuxmobile/hyprland-dots)©
[Owl4ce](https://github.com/owl4ce) © [Ilham25](https://github.com/ilham25) ©
[Siduck](https://github.com/siduck) © [NvChad](https://github.com/NvChad) ©
[Rxyhn](https://github.com/rxyhn) © [AmitGold](https://github.com/AmitGolden)

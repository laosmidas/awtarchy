# `arch dilla.hypr.files`

**Click the image below to see more previews!**

[![overview](https://github.com/laosmidas/arch-hypr-dots/raw/main/previews/overview.png)](https://github.com/laosmidas/arch-hypr-dots/tree/main/previews.md)

## 🚀 Quick Start
ℹ️ Note: Before running `archinstall`, update the package database to ensure you're using the latest version:
```bash
pacman -Syyu
```

### Installation (after `archinstall`):
```bash
git clone https://github.com/laosmidas/arch-hypr-dots
cd arch-hypr-dots
chmod +x setup_installer.sh
sudo ./setup_installer.sh
```
> ⚠️ Caution: Always review scripts from the internet before running them.

## 🖥️ System Overview

| Component          | Details |
|--------------------|---------|
| **Distro**         | [Arch Linux](https://archlinux.org/) |
| **Installation**   | [archinstall](https://github.com/archlinux/archinstall) |
| **File System**    | [ext4 (separate root/home partitions)](https://man.archlinux.org/man/ext4.5.en) and/or [BTRFS](https://wiki.archlinux.org/title/Btrfs) |
| **Repositories**   | core, extra, multilib, [AUR](https://aur.archlinux.org/), [Flathub](https://flathub.org/) |
| **Terminal**       | [Alacritty](https://github.com/alacritty/alacritty) |
| **Bootloader**     | [systemd-boot](https://man.archlinux.org/man/systemd-boot.7) |
| **Window Manager** | [Hyprland](https://github.com/hyprwm/Hyprland) ([config](https://github.com/laosmidas/arch-hypr-dots/tree/main/config/hypr)) |
| **Kernel**         | [linux-tkg](https://github.com/Frogging-Family/linux-tkg) with BORE scheduler |

## 🎨 Wallpaper Collections
- [dharmx/walls](https://github.com/dharmx/walls)
- [Gruvbox Wallpapers](https://github.com/AngelJumbo/gruvbox-wallpapers)
- [Aesthetic Wallpapers](https://github.com/D3Ext/aesthetic-wallpapers)

---

# ⌨️ Hyprland Keybindings

> 💡 `$mod = ALT`, `$super = SUPER`, `$rotate = ALT or SUPER` (toggled by `rotate_mod.sh`)

## 🛠️ Custom Scripts & Applications
| Keybind                 | Action                                                  |
|-------------------------|---------------------------------------------------------|
| `SUPER + r`             | Rotate navigation keys (toggle SUPER/ALT)               |
| `SUPER + t`             | Run theme switcher script                               |
| `SUPER + w`             | Launch or kill Waypaper (wallpaper GUI)                 |
| `SUPER + q`             | Scan QR code using Flameshot + ZBar                     |
| `SUPER + SHIFT + s`     | Take cropped screenshot                                 |
| `SUPER + SHIFT + f`     | Take fullscreen screenshot                              |
| `SUPER + SHIFT + g`     | Record cropped GIF using ffmpeg                         |
| `ALT/SUPER + SHIFT + c` | Launch SpeedCrunch (calculator)                         |
| `ALT + SHIFT + Enter`   | Launch terminal (Alacritty)                             |
| `ALT + SHIFT + b`       | Launch btop in terminal                                 |
| `ALT + SHIFT + h`       | Launch htop in terminal                                 |
| `ALT + p`               | Launch Wofi (app launcher)                              |
| `ALT + SPACE`           | Dismiss notifications (makoctl)                         |
| `SUPER + p`             | Launch or kill wlogout                                  |
| `SUPER + i`             | Launch hyprpicker (color picker)                        |
| `SUPER + m`             | Toggle audio mute (wpctl)                               |
| `SUPER + l`             | Lock screen (hyprlock)                                  |
| `ALT/SUPER + v`         | Launch or kill pavucontrol (audio control)              |

## 🪟 Window & Workspace Management
| Keybind                         | Action                                        |
|----------------------------------|----------------------------------------------|
| `ALT/SUPER + SHIFT + q`         | Close focused window                          |
| `ALT + f`                       | Toggle floating window                        |
| `ALT + y`                       | Pin focused window                            |
| `ALT/SUPER + CTRL + f`          | Toggle fullscreen                             |
| `ALT/SUPER + ←/→/↑/↓`           | Move focus between windows                    |
| `ALT/SUPER + SHIFT + ←/→/↑/↓`   | Move active window within workspace           |
| `ALT/SUPER + CTRL + SHIFT + ←/→/↑/↓` | Move active workspace to another monitor |
| `ALT/SUPER + 1-0`               | Switch to workspace 1–10                      |
| `ALT/SUPER + SHIFT + 1-0`       | Move window to workspace 1–10                 |
| `ALT/SUPER + x`                 | Toggle scratchpad workspace (`magic`)         |
| `ALT/SUPER + SHIFT + x`         | Move window to scratchpad (`magic`)           |

## 🎛️ Resize & Move Windows
| Keybind                      | Action                        |
|------------------------------|-------------------------------|
| `ALT/SUPER + CTRL + ←/→`     | Resize window horizontally    |
| `ALT/SUPER + CTRL + ↑/↓`     | Resize window vertically      |
| `ALT/SUPER + Mouse Left`     | Move window (floating)        |
| `ALT/SUPER + Mouse Right`    | Resize window (floating)      |

## 🔊 Media & Display Keys
| Keybind                  | Action                                   |
|--------------------------|------------------------------------------|
| `XF86AudioRaiseVolume`   | Increase volume (wpctl)                  |
| `XF86AudioLowerVolume`   | Decrease volume (wpctl)                  |
| `XF86AudioMute`          | Toggle speaker mute (wpctl)              |
| `XF86AudioMicMute`       | Toggle mic mute (wpctl)                  |
| `XF86MonBrightnessUp`    | Increase brightness (brightnessctl)      |
| `XF86MonBrightnessDown`  | Decrease brightness (brightnessctl)      |
| `XF86AudioPlay`          | Play/pause media (`play_pause.sh`)       |
| `XF86AudioNext`          | Next media track (playerctl)             |
| `XF86AudioPrev`          | Previous media track (playerctl)         |

## 🧪 Miscellaneous
| Keybind            | Action                                      |
|--------------------|---------------------------------------------|
| `ALT/SUPER + F12`  | Display current Hyprland version in notify  |

---

## ⚡ Installation Scripts
- [Arch Repo Apps](scripts/install_arch_repo_apps.sh)
- [AUR Apps](scripts/install_aur_repo_apps.sh)  
- [Flatpak Apps](scripts/install_flatpak_apps.sh)

> ℹ️ Modify scripts to suit your preferences

## 🌐 Browser Notes
- [Brave](browser_notes/brave.md)
- [Ungoogled-Chromium](browser_notes/ungoogled-chromium.md)
- [Firefox Privacy Forks](browser_notes/firefox_privacy_focused_forks.md)
- [Cromite](browser_notes/cromite.md)

---

## 📜 License
All code and notes are unlicensed - use freely!  
[See UNLICENSED file](https://github.com/laosmidas/arch-hypr-dots/blob/main/UNLICENSED)

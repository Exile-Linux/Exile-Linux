# EXILE LINUX
### Minimalist De-Corped Linux
![Exile Linux Wallpaper](airootfs/usr/share/backgrounds/ExileLinuxWallpaper.jpg)

Exile Linux is a specialized, Arch based Linux Distribution designed to escape corporate greed, the aim is to remove any proprietary software. We used Arch as it is a build it yourself distribution, which matches out values, when you install Exile Linux, it is entirely yours to do with as you please, you can break it if you want or modify the code to your liking.

---

## Technical Overview
It is still in development but the live environment is booting as designed.

* **Core Architecture:** Arch Linux x86_64
* **Desktop Interface:** KDE Plasma 6 (Wayland)
* **Default Typography:** JetBrains Mono
* **System Shell:** Zsh
* **Boot Compatibility:** UEFI (Systemd-boot) and BIOS (Syslinux)

## System Specifications
| Component | Implementation |
| :--- | :--- |
| **Base Distribution** | Arch Linux |
| **Windowing System** | Wayland |
| **User Interface** | Plasma 6 |
| **Primary Font** | JetBrains Mono |
| **Session Type** | Live / Amnesic |
| **Init System** | Systemd (an ExileInit is in development, this is just temporary.) |

## Build Procedure
Building the Exile Linux ISO requires a host system running Arch Linux with the `archiso` package installed.

1. **Install Build Dependencies**
   ```bash
   sudo pacman -S archiso git


---

> **Development Status:** Exile Linux is currently in an active prototype phase. This software is provided "as is" for testing and development purposes. System stability, security features, and hardware compatibility are subject to change as the project matures.

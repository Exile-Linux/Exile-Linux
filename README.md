# EXILE LINUX
### Minimalist Amnesic Environment

![Exile Linux Wallpaper](airootfs/usr/share/backgrounds/ExileLinuxWallpaper.jpg)

Exile Linux is a specialized, Arch-based live environment engineered for security, privacy, and technical precision. Utilizing the KDE Plasma 6 desktop environment on the Wayland protocol, it provides a volatile, high-performance workspace designed for digital sovereignty.

---

## Technical Overview
Exile Linux operates as an amnesic system, ensuring that each session begins from a clean state. It is designed to serve as a secure baseline for rescue operations, security auditing, and private computing.

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
| **Init System** | Systemd (an ExileInit is in development, this is just temporary. |

## Build Procedure
Building the Exile Linux ISO requires a host system running Arch Linux with the `archiso` package installed.

1. **Install Build Dependencies**
   ```bash
   sudo pacman -S archiso git


---

> **Development Status:** Exile Linux is currently in an active prototype phase. This software is provided "as is" for testing and development purposes. System stability, security features, and hardware compatibility are subject to change as the project matures.

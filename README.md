# MSIntosh with OpenCore Bootloader - Monterey (12.4)
## OpenCore Version : 0.7.9
![SystemInfo](https://raw.githubusercontent.com/kpratama24/MSIntosh/master/Screenshot/Monterey/Overview.png)

# Hardware

- CPU: Intel(R) CPU Core i5-4570
- Mainboard: MSI B85-G43 GAMING
- RAM: Corsair Vengeance DDR3 1666Mhz (4GBx2) 
- SSD:
    - V-GEN 03SM22AR/512GB
    - WDC WDS120G2G0A/120GB
- HDD:
    - Seagate ST1000XXX/1TB
- Wireless: TP Link TL-WR823n V3 (USB)
- Bluetooth : Cambridge Silicon Radio (a12)
- Ethernet : Atheros KillerE2200 
- VGA:
  - Intel HD Graphics 4400(Onboard)
  - PowerColor AMD RX 550 640SP 2GB
- Audio Codec : Realtek ALC1150
- Monitors:
  - Samsung SA300 18,4 Inch (1366x768)
- Power: Corsair VS Series™ VS550 — 80 PLUS® (550 watt)
- Mouse: Digital Alliance Luna Gaming Mouse
- Keyboard: Logitech K200 Keyboard
  
# Installation
 Updating...
# BIOS
 - Restore defaults
 - Set Boot Mode to UEFI

# What works
 - iMessage, Facetime, App Store
 - RX 550 640SP AMD GPU
 - NVRAM (Native)
 - Ethernet + Wireless + Bluetooth (No handoff because of non-internal)
 - USB 2.0/3.0 Ports
 - Shutdown & Restart
 - USB (without 15 Port Limit Patch)
 - DRM (`shikigva approach`)
    - iTunes Video (v1)
    - Amazon Prime (v2)
    - Netflix (v3)
    - Apple TV+ (v4)
 - Sounds (Microphone (boosted), Rear Jack, Output. Native AppleHDA)
 - Dual-boot via OpenCore boot menu (Windows 10 + macOS Monterey)
 - Desktop Power Management

# What isn't works (yet)
 - Sleep (MSI firmware bug. Just disable it via built-in Apple System Preferences)


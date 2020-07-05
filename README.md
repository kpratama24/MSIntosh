# MSIntosh with OpenCore Bootloader - Catalina (10.15.5)
![SystemInfo](https://raw.githubusercontent.com/kpratama24/MSIntosh/master/Screenshot/Catalina/Overview.png)

# Hardware

- CPU: Intel(R) CPU Core i3 4150
- Mainboard: MSI B85-G43 GAMING
- RAM: Corsair Vengeance DDR3 1666Mhz (4GBx2) 
- SSD:
    - KINGSTON SA400S37/120GB
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

# What works
 - RX 550 AMD GPU
 - Ethernet + Wireless + Bluetooth (No handoff because of non-internal)
 - USB 2.0/3.0 Ports
 - Shutdown & Restart
 - DRM
    - iTunes Video (v1)
    - Amazon Prime (v2)
    - Netflix (v3)
    - Apple TV+ (v4)
 - Sounds (Microphone (boosted), Rear Jack, Output. Native AppleHDA)
 - Desktop Power Management

# What isn't works (yet)
 - Sleep / Wake (MSI firmware bug. Just disable it via built-in Apple System Preferences)
 - Bootstrap.efi (DON'T EVER USE IT. Otherwise, you will brick the boot sequence. Wait for OpenCore team to fix the issue)
 - USB Power (Too lazy to follow the guide)


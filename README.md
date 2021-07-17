# Hackintosh Build

[![macOS](https://img.shields.io/badge/macOS-11.2.3-orange)](https://www.apple.com.cn/macos/big-sur-preview/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.3-9cf)](https://github.com/acidanthera/OpenCorePkg)

This is my first Hackintosh, running macOs Big Sur and completing my Dual Boot PC (macOS / PopOS!), bye Windows...

![macOS](https://github.com/gusmendez99/hackintosh/blob/master/images/about.png?raw=true)

- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide)

**macOS Version: 11.2.3 (Big Sur)**

**OpenCore Version: 0.6.3**

## PC Build

Type|Item
:----|:----
**CPU** | Intel - Core i5-10400F
**CPU Cooler** | AZZA Blizzard 120mm
**Motherboard** | ASUS TUF Gaming B460M-PLUS WIFI
**Memory** | TEAMGROUP T-Force Vulcan Z 16GB
**Storage (macOS)** | SSD Western Digital GREEN 240GB M.2 
**Storage (Windows & PopOS!)** | SSD KINGSTON A400 480GB
**Video Card** | ASUS Dual RX 5500XT EVO 4GB
**WiFi + Bluetooth** | Intel® WiFi 6 AC 3168, Bluetooth 5.1
**Case** | Cooler Master Q300L
**Power Supply** | EVGA 600W 80+
**Monitor 1** | HP 27y
**Monitor 2** | HP v27i


## What's working

### Working

- [x] iCloud
- [x] iMessage
- [x] FaceTime
- [x] Virtualization (VirtualBox)
- [x] Sleep
- [x] WiFi / Bluetooth
- [x] Sound

### Not tested (yet)

- [ ] Airdrop

## Important

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code.
How-To: [config.plist Setup](https://dortania.github.io/OpenCore-Install-Guide/config.plist/#adding-your-ssdts-kexts-and-firmware-drivers)

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>ESIzRFVm</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac19,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```

### Updates

- **2021-03-30**: OC 0.6.3 & Big Sur.
- **2021-07-16**: New fresh install after MoBo short circuit months ago haha.

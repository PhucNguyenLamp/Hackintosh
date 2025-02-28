# MSI-GF63-THIN-9RCX-646VN-OPENCORE-HACKINTOSH

MSI GF63 9RCX OpenCore 1.0.1 Sonoma 14.6

Guided by: https://dortania.github.io/OpenCore-Install-Guide/

Insert your own Platforminfo in config.plist

# Configuration


| Specifications      | Detail        |
| ------------- |:-------------:|
| Computer model    | GF63 Thin 9RCX 646VN 15.6" (GTX 1050Ti) |
| Processor      |  Intel® Core™ i5-9300H @2.40Ghz      |
| Memory | 2x8 GB DDR4 2666 Mhz     |
|    Disk   |    SSD Crucial MX500 3D NAND Sata III 500GB   |
| Integrated Graphics | Intel® UHD Graphics 630 |
| Display  | IPS FHD 1920x1080 (15.6 inch) @60Hz |
| Sound Card     | Realtek Audio ALC269   |
| Wireless | Intel® Wireless-AC 9560 160MHz  |
| Ethernet | Realtek PCIe GBE Family Controller  |

# Change BIOS settings

- Show hidden settings with: CTRL Right + SHIFT Right + ALT Left + F2

## Turn off 

- Secure Boot [Security]
- CFG Lock [Advanced -> Power & Performance -> CPU -> CPU Lock Configuration]
- Fast Boot [Boot]
- Turn off VT-d

## Other configs

- Select UEFI mode without CSM [Boot]
- Set SATA Mode: AHCI

# Works

- [x] All USB Ports
- [x] Wifi
- [x] Ethernet
- [x] Keyboard
- [x] Trackpad
- [x] Bluetooth
- [x] Audio
- [x] Battery status
- [x] HDMI Port
- [x] Boot without USB (Use EasyUEFI for Windows)

# Not Works - Yet

- [ ] Fan Speed (Common problem MSI Notebook)
- [ ] iMessage

# Never Gonna Work

- [ ] AirDrop & Facetime (Need Native WiFi Card)
- [ ] Nvidia RTX 1050Ti 4GB (Switchable Graphics is not supported by newer Hackintosh)

# Screenshot

![ảnh](https://github.com/user-attachments/assets/ea019e5d-90c0-4de1-8834-a882c5d2d0db)


# Template credits from the chads i found on githubs
- https://github.com/rahulhingve/Hackintosh-MSI-GF63-Thin-9SCXR
- https://github.com/mykimy/MSI-GF63-9RCX_OpenCore-Hackintosh
- https://github.com/X1er0/MSI-GF63-THIN-10SC-OPENCORE-HACKINTOSH

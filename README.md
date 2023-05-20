# Dell-Vostro-5590-Hackintosh-EFI
EFI for Dell Vostro 5490/5590 on OpenCore 0.9.2
Inspiron 5490/5498/5590/5598 may also be universal
Surpport Macos 13 Ventura
## Perhaps the most fully functional VOSTRO 5590/5490's EFI

### Specs:
Type | Details
| -------------- |:----------------------------:|
CPU | Intel Core i7-10510U
iGPU | Intel UHD 620
dGPU | NVIDIA GeForce MX250
Display | 1920x1080
RAM | 16GB
Audio | Realtek ALC236
WLAN | Intel 9462AC
LAN | Realtek RTL8169
SSD | 480GB Kingston A400 - macOS boot
NVMe | 1T Micron 2200s - Windows (not surpport Macos, have blocked by boot-args "nvme = -1")
KB | Built-in Standard PS2 Keyboard
TP | Built-in I2C HID Trackpad
SMBIOS | MacBookPro15,4
Bootloader | OpenCore 0.9.2

### Set up your bios first
* UEFI Boot Path Security - Never
* Integrated NIC - Enabled
* SATA Operation - AHCI
* USB Configuration - Enable USB Boot Support must be checked
* Disable EcoPower (Optional)
* Absolute - Disable Absolute
* TPM 2.0 Security On - OFF
* Intel SGX - Disabled
* Enable Secure Boot - OFF
* Secure Boot Mode - Deployed Mode
* Intel Virtualization Technology - ON
* VT for Direct I/O - OFF

### What works and What doesn't or WIP:
- [x] Intel UHD 620 iGPU eDP Output (with Backlight)
- [x] Intel UHD 620 iGPU HDMI Output
- [x] ALC236 Internal Speakers
- [x] ALC236 Native Jack Output
- [x] ALC236 HDMI Audio Output
- [x] All USB Ports Type A (2xUSB 3.0 and 1xUSB 2.0)
- [x] SpeedStep / Sleep / Wake
- [x] I2C Touchpad
- [x] Intel Bluetooth Module (on Ventura)
- [x] Realtek RTL8169 LAN
- [x] ACPI Battery
- [x] NVRAM
- [x] WiFi (on Ventura)
- [x] USB Cardreader
- [x] Internal Camera
- [x] DisplayPort over Type-C
- [ ] Internal Mic (not surpport)
- [ ] MX250 dGPU (Not supported)

### Contact me
E-mail:1820031511@qq.com

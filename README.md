# Dell-Vostro-5590-Hackintosh-EFI
Dell Vostro 5590 Hacintosh EFI OC0.8.3(support macos13 ventura beta3)

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
NVMe | 1T Micron 2200s - Windows
KB | Built-in Standard PS2 Keyboard
TP | Built-in I2C HID Trackpad
SMBIOS | MacBookPro15,2
Bootloader | OpenCore 0.8.3

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
- [x] Wi-Fi (on Ventura)

- [ ] USB Cardreader
- [ ] DisplayPort over Type-C (did not check)
- [ ] MX250 dGPU (Not supported)
- [ ] Internal / External Mic and Camera

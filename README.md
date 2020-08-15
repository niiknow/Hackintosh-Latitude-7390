# Dell Latitude-7390 (non 2-in-1 model) OpenCore Hackintosh
> So I can keep MY7390 Hackintosh up-to-date

* i7-8650U, 32gb DDR4
* Replace wifi with Broadcom BCM43xx (Dell 1560)
* Replace storage with 1TB Sabrent Rocket Q


## Software
* OpenCore 0.6 - Kaby Lake sytem need opencore 0.6+
* Catalina 10.15.6


## Something you may want to apply

**Click by trackpad:**
System Preferences - Trackpad - Tap to click

**Drag by trackpad:**
System Preferences - Accessibility - Mouse & Trackpad - Trackpad Options... - Enable Dragging

**Change trackpad tracking speed**
System Preferences - Trackpad - Tracking Speed

**Enable HiDPI:**
Run the following command by terminal

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"`


**Generate SMBIOS**
Remember to use https://github.com/corpnewt/GenSMBIOS and generate unique smbios for your system.

## Key mapping

You can modify this in System Preference - Keyboard -Modifier Keys...
Ctrl - Control

Fn - Fn

Win - Option

Alt - Command


## Credit
original work: https://github.com/Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI/tree/Catalina-OpenCore
xzhih/one-key-hidpi：https://github.com/xzhih/one-key-hidpi
generate smbios: https://github.com/corpnewt/GenSMBIOS

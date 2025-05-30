# hp-elitebook-840-g3-hackintosh-efi

EFI for the HP Elitebook 840 G3

Prebuilt opencore EFI for macos (for the hp elitebook 840 G3)

- Note: I don't use anymore hp elitebook 840 G3 since I got a macbook air M3, but I continue to update this repo

# Laptop Specs
- CPU : intel core i5 6200U
- GPU : Integrated Intel HD Graphics 520
- Wifi/Bluetooth : Intel Wireless AC 8260
- Audo codec : Conexant CX20724
- Memory : 8192 (8GB) Ram DDR4

# Supported MacOS Version
- [sequoia 15.x.x (tested)](https://github.com/GeantW0rld/hp-elitebook-840-g3-hackintosh/tree/main/MacOS%20sequoia%2015.x) (for use wifi please use Heliport and the kext itlwm)
- for older of macos (like sonoma or ventura) --> please use the kext AirportItlwm
- No support for BETA version or another model of HP brand (please ask to Hackintosh community), this efi is exclusively for HP Elitebook 840 G3

# Bios Settings

![Screenshot](https://github.com/GeantW0rld/hp-elitebook-840-g3-hackintosh-efi/blob/main/Images/IMG_20240223_221044.jpg)

![Screenshot](https://github.com/GeantW0rld/hp-elitebook-840-g3-hackintosh-efi/blob/main/Images/IMG_20240223_221054.jpg)

![Screenshot](https://github.com/GeantW0rld/hp-elitebook-840-g3-hackintosh-efi/blob/main/Images/IMG_20240223_221105.jpg)

# What's work

- Graphics
- Battery
- Audio
- wifi and Bluetooth (for use wifi please use Heliport and the kext itlwm)
- Internet
- DP and VGA
- Key
- Trackpad (Before MacOS 15.x the Trackpad is not fixed with VoodooRMI, please check https://github.com/VoodooSMBus/VoodooRMI for more info for installation (EFI For MacOS 15+ have VoodooRMI and VoodooSMBus))

# Some screenshots

![Screenshot](https://github.com/GeantW0rld/hp-elitebook-840-g3-hackintosh-efi/blob/main/Images/mac15.png)

# Support
You can support me by buying a coffee for 1€ 😊

<a href="https://www.buymeacoffee.com/geantworld" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

# Credits

[Dortania](https://dortania.github.io/OpenCore-Install-Guide/) - Made the OpenCore guide

[itlwm](https://github.com/OpenIntelWireless/itlwm) - for Intel wifi | bluetooth

[Acidanthera](https://github.com/acidanthera) - OpenCore Bootloader |  AppleALC | BlueToolFixup | IntelMausi | Lilu | VirtualSMC | WhateverGreen | etc

[Apple](https://www.apple.com/) - Made MacOS

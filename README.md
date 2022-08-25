# ASRock B460M PRO4 OpenCore EFI
EFI for ASRock B460M PRO4 + I5 10400F + PowerColor AMD Radeon RX570 4GB

This Hackintosh is based on OpenCore `0.8.2` and `MacOS Big Sur 11.6.8` I used [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/) for [Comet Lake](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#starting-point).
![](https://raw.githubusercontent.com/mr00k3/asrock-b460m-pro4-oc-efi/main/screenshots/Screenshot%202022-08-25%20at%2014.38.48.png)

### Notes
    USB ports are not mapped
    Hibernation and Sleep don't work
    Built without WIFI and Bluetooth card

## Hackintosh Specs
* CPU: Intel Core i5-10400F
* GPU: PowerColor AMD Radeon RX570 4GB
* MOBO: ASRock B460M PRO4
* RAM: HyperX Fury RGB 16GB (2x8GB) 2666MHz
* SSD M.2: WD SN550 500GB 

## BIOS
* Disabled Secure Boot
* VT-x: ON
* FastBoot: OFF

## SSDTs

Compiled using [SSDTTime](https://github.com/corpnewt/SSDTTime)

* SSDT-AWAC
* SSDT-EC
* SSDT-PLUG

## Kexts

All kexts downloaded from official repo

* [AppleALC.kext](https://github.com/acidanthera/AppleALC) - Audio
* [IntelMausi.kext](https://github.com/acidanthera/IntelMausi) - Ethernet
* [Lilu.kext](https://github.com/acidanthera/Lilu) - Patches
* [NVMeFix.kext](https://github.com/acidanthera/NVMeFix) - Something for NVMe drive
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC) - SMC emulator
* [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) - Graphics patches

### Plist

* Serial Numers are generated

## PlatformInfo

* iMac20,1

## Source Code

- [OpenCore bootloader](https://github.com/acidanthera/OpenCorePkg)
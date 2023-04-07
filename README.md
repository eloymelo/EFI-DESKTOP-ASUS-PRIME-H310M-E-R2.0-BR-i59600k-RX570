# Asus Prime H310M-E R2.0/BR + i59600K + RX 580 2048SP (VBIOS RX 570)

![about-12 3 1](https://github.com/eloymelo/EFI-DESKTOP-ASUS-PRIME-H310M-E-R2.0-BR-i59600k-RX570/blob/main/Images/aboutthismac.png?raw=true)

**SMBIOS: iMacPro1,1**
<br>
**Latest working macOS**: Ventura 13.3
<br>
**Current OpenCore**: 0.9.1

## Complete hardware specs
- Intel i5 9600K
- Asus Prime H310M-E R2.0/BR
- RX 580 2048SP (VBIOS Sapphire.RX570.8192.191031)
- 2x 16Gb DDR4 2400Mhz Hyperx with XMP Disabled
- FV-A436CD Wireless Card

## What works
- macOS Catalina, macOS Big Sur, macOS Monterey and macOS Ventura
- Audio
- All USB ports
- iCloud related services (Drive, iMessage, Facetime, etc)
- Temperature monitoring for everything
- DRM content (Netflix, AppleTV, etc)
- Shutdown/Reboot/Update to newer macOS builds over time
- AirDrop
- Wifi
- Bluetooth

## What doesn't work/Bugs
- Everything working so far

## Kexts used:
- AppleALC.kext
- Lilu.kext
- NVMeFix.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Keep in mind:
- Don't forget to set to dGPU (PCIe) instead of iGPU (Primary Display CPU) and also to disable iGPU Multi-Monitor in your BIOS settings if you intend to use this alongside the dedicated graphics card (dGPU).  

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- Gabriel Luchina - Universo Hackintosh (https://github.com/luchina-gabriel)

## Discord - Universo Hackintosh (With English Support)
- [Access Discord](https://discord.universohackintosh.com.br)

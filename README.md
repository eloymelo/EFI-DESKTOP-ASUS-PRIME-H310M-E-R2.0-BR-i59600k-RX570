# Asus Prime H310M-E R2.0/BR + i59600K + RX 580 2048SP (VBIOS RX 570) + Fenvi AXE3000(AX210)

![about-12 3 1](https://github.com/eloymelo/EFI-DESKTOP-ASUS-PRIME-H310M-E-R2.0-BR-i59600k-RX570/blob/main/Images/aboutthismac.png?raw=true)

**SMBIOS: iMacPro1,1**
<br>
**Latest working macOS**: 12.6.1
<br>
**Current OpenCore**: 0.8.7

## Complete hardware specs
- Intel i5 9600K
- Asus Prime H310M-E R2.0/BR
- RX 580 2048SP (VBIOS Sapphire.RX570.8192.191031)
- 2x 16Gb DDR4 2400Mhz Hyperx with XMP Enabled
- Wifi/BT AXE3000(AX210) 

## What works
- macOS Catalina, macOS Big Sur and macOS Monterey
- Audio
- All USB ports
- iCloud related services (Drive, iMessage, Facetime, etc)
- Temperature monitoring for everything
- DRM content (Netflix, AppleTV, etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work/Bugs
- Sometimes the operating system freezes and restarts

## Kexts used:
- AirportItlwm.kext
- AppleALC.kext
- BlueToolFixup.kext
- IntelBluetoothFirmware.kext
- IntelBTPatcher.kext
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
- Don't forget to set to dGPU (PCIe) instead of iGPU (Primary Display CPU) in your BIOS settings if you intend to use this alongside the dedicated graphics card (dGPU).  

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- Gabriel Luchina - Universo Hackintosh (https://github.com/luchina-gabriel)

## Discord - Universo Hackintosh (With English Support)
- [Access Discord](https://discord.universohackintosh.com.br)

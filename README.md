# Gigabyte B460M Aorus Elite + i9 10900 ES + AMD Radeon RX 580 + iGPU

![About This Mac - General](https://raw.githubusercontent.com/viniciuspetrachin/EFI-GIGABYTE-B460M-ELITE-i9-10900-ES-RX-580-WITH-UHD-630/main/Details/about%20this%20mac.png)

**Latest working macOS**: 13.3
<br>
**Current OpenCore**: 0.9.2

## Complete hardware specs
- Intel i9 10900 ES (Engineer Sample / QTB1)
- Gigabyte B460M Aorus Elite
- Realtek® ALC1200 codec
- iGPU Intel UHD 630
- WC DeepCool Gammaxx L240T Blue
- 2x 8Gb DDR4 2933Mhz Team Group
- SSD NVME Gen3 - XPG 512Gb

## What works
- macOS macOS Monterey, macOS Ventura (13.3 tested and working)
- Audio
- HDMI/DP
- USB ports
- Everything iCloud related (Drive, iMessage, Facetime, etc)
- Temperature monitoring for everything
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- N/A

## Config.plist
Remember to configure your config.plist with the information you generate in your GenSMBIOS. I left everything with code AAAAA. For you to update.

![Config.plist Sample MLB](https://raw.githubusercontent.com/viniciuspetrachin/EFI-GIGABYTE-B460M-ELITE-i9-10900-ES-RX-580-WITH-UHD-630/main/Details/config%20plist%20gensmbios.png)

## Kexts used:
- AppleALC.kext
- IntelMausi.kext
- Lilu.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBInjectAll.kext
- VirtualSMC.kext
- WhateverGreen.kext
- NVMeFix.kext

## Notes
Although all USBs work, it is still necessary to map the ports in specific cases for some hardware, such as a wifi module if you put the part. Search on how to map, I recommend Gabriel Luchina's channel that he explains in detail.

## Geekbench Results:
- Inside `Details` directory

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 10th Intel Gen - Comet Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-10THGEN-COMET-LAKE)

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)

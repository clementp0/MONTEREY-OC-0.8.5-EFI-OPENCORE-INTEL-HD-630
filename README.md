
  

# OPENCORE 0.8.4 EFI using I9 10850K and INTEL HD 630 - Monterey

<p align="center">
  <img src="https://github.com/clementp0/MONTEREY-OC-0.8.5-EFI-OPENCORE-INTEL-HD-630/assets/15802129/8635340e-5f18-4102-ad47-c942a31df9c01">
</p>


**Latest tested macOS**: Monterey 12.6

  

**Current OpenCore**: 0.8.4

  
See [documentation](https://dortania.github.io/GPU-Buyers-Guide/modern-gpus/intel-gpu.html#kaby-lake-refresh-coffee-lake-coffee-lake-refresh-whiskey-lake-comet-lake-8xxx-9xxx-10xxx)

  
  

## Complete hardware specs

  

- Intel i9 10850k
- ROG STRIX Z490-F GAMING
- INTEL HD 630 **(used for opencore)**
- GIGABYTE RTX 3070 Gaming OC **(not used for opencore)**
- 32GB RAM Corsair Vengance - 3200 MHz DDR4

  

## What works

  

- macOS Monterey 12.6

- WiFi (using [itlwm](https://github.com/OpenIntelWireless/itlwm) + [heliport](https://github.com/OpenIntelWireless/HeliPort))

- Audio
- HDMI/DP
- All USB ports
- 2x 2.5Gbit Ethernet
- Everything iCloud related (Drive, iMessage, Facetime, etc)
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot
- Deep Sleep

  

## What doesn't work

  

- (oob) WiFi and Bluetooth + Airdrop + Sidecar..
*(will be fixed with BCM94360CD card)*

  

## Kexts used:

  

- Lilu.kext
- itlwm.kext
- Lilu.kext
- USBInjectAll.kext
- VirtualSMC.kext
- WhateverGreen.kext
-  *Other Kext needed for my config (and residuals)*


## How to use it ?

  

⚠️ Dont forget to recreate the _plateforminfo_ section and change SMBIOS data (using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) or any other tool) ⚠️

  
## Thanks/Credits

  
- [Opencore Team](https://dortania.github.io/getting-started/)

### Disclaimer 
*Some residual SSTD or Kext may be present but not used (the same EFI is used on different hardware configurations)*

# Z370N-Wifi OpenCore

This is my WIP OpenCore setup for the Z370N-Wifi board.

## My Specs

- Z370N-Wifi
- EFI F10
- Core i7 8700K
- 32GB RAM (2x16GB)
- Samsung 970 EVO 1TB
- Apple wifi/bt card from MacBook Air 
- Apple Magic Keyboard / Magic trackpad
- RX 560
- Integrated Graphics Enabled
- Samsung 28" 4K monitor


## What works

- Catalina install
- Sleep
- All devices
- Most DRM 

## What doesn't / Still to do

- USB Mapping
- CFG LOCK patching of EFI
- CPU PM states (if I decide to do that)
- Enable and test Wake on lan


## Notes

Only SSDT-EC-USBX and SSDT-PLUG are necessary. EFI F10 still uses RTC and not AWAC timer. Other coffee lake SSDT don't apply to the Z370 chipset because it's not really a 300 series, but a rebranded 200 series.
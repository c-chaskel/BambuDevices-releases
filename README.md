# BambuDevices Firmware Releases

This repository hosts firmware binaries for OTA updates.

## Devices

- **PrintGlow** - ESP32-S3-Zero LED status indicator for Bambu Lab printers
- **PrintDeck** - ESP32-S3 touchscreen display for multi-printer monitoring

## Usage

Devices automatically check `firmware/version.json` for updates.
Updates can be installed from the device's web interface (System page).

## Files

- `firmware/version.json` - Version metadata
- `firmware/printglow.bin` - PrintGlow firmware
- `firmware/printdeck.bin` - PrintDeck firmware

## License

Copyright (c) 2024 c-chaskel. All rights reserved.

Firmware binaries are provided for personal use with BambuDevices hardware.
Redistribution, modification, or commercial use requires a license.

For licensing inquiries, visit: https://github.com/c-chaskel

# LayerGlance firmware releases

Signed firmware files for over-the-air updates of LayerGlance devices.
Devices download `firmware/version.json` and the matching firmware file,
and install an update only if its signature verifies.

## Devices

- **LayerGlance Touch** (`firmware/printdeck.bin`): ESP32-S3 touchscreen for monitoring several printers.
- **LayerGlance Glow** (`firmware/printglow.bin`): ESP32-S3-Zero LED status light.

## Licence

Copyright (c) 2024-2026 FiddlerCrab UG (haftungsbeschränkt), Berlin, Germany.
All rights reserved.

These files are proprietary. They are published here only so that
LayerGlance devices can update themselves. They are not released under an
open-source licence. You may not copy, redistribute, modify, decompile or
otherwise reverse engineer them, except where the law expressly permits this
and it cannot be excluded by contract. Use is governed by the LayerGlance
licence and sale terms. Third-party components inside the firmware are
licensed under their own terms, which apply only to those components.

Contact: FiddlerCrab UG (haftungsbeschränkt), Balbronner Straße 4,
14195 Berlin, Germany, hello@fiddlercrab.eu

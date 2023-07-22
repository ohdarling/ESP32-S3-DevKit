# ESP32-S3-DevKit
A minimal ESP32-S3 dev kit that is compatible with usual breadboard, featuring dual USB Type-C ports and exposing all available GPIO pins.

![esp32-s3-devkit](https://github.com/ohdarling/ESP32-S3-DevKit/raw/main/images/esp32-s3-devkit.jpg?raw=true)

## Features

- 1000mil ultra-slim design, can be inserted into common breadboards and retains an additional column of pin headers on each side for easy peripheral connection.
- Exposes all available GPIO pins (EN, IO0, 19 and 20 for USB, 43 and 44 for UART, 35, 36, and 37 for PSRAM are not exposed).
- Dual USB Type-C ports, one for ESP32-S3 USB and one for CH340C, allowing for simultaneous debugging of USB devices and serial logs.
- All surface-mount components are 0805 for easy manual soldering (except for USB Type-C ports and transistors).
- 4 sets of 3.3V and 2 sets of 5V power supplies, eliminating the need for power and ground pins when connecting external devices.
- Supports USB automatic firmware download and burning.
- Equipped with USB-C identification resistors, supporting C-C data line power supply and debugging.

## Schenmatic

![esp32-s3-devkit-schenmatic](https://github.com/ohdarling/ESP32-S3-DevKit/raw/main/images/esp32-s3-devkit-schenmatic.png?raw=true)

## Files

* ESP32S3-DevKit-Schenmatic: Schenmatic for this devboard
* ESP32S3-DevKit-Gerber: Gerber file used for manufacturing PCB
* ESP32S3-DevKit-BOM: BOM table
* ESP32S3-DevKit-SolderHelper: Interactive soldering assistant tool

## Links

* [为什么要做这个开发板](https://xujiwei.com/blog/2023/07/esp32-s3-devkit-diy/)
* [OSHWHub 开源工程](https://oshwhub.com/wandaeda/dan-pian-ji-esp32-s3-kai-fa-ban)

## License

MIT
# moyoECG 
moyoCG - very small wearable ECG device that sends raw and processed data over BLE

**This is an old repository - new version is located here: https://github.com/AuroraHealth12/moyoECG (and is divided into multiple repositories for relevant parts of the project, links are in description)**

Project is in active development stage, at the current moment we have shared:
 * schematics and PCB design
 * ECG monitor program based on Node.js, cross-platform
 * ECG monitor program for Linux (outdated: might not work properly, please use cross-platform version instead)
 * Firmware for the main unit, rather stable and reliable build. Next planned major update will cover better beat detection and more robust bpm processing. 
 * Firmware for the base unit that supports uploading moyoECG firmware via radio
 * Android app with major rework, quite stable now
 * bootloader code for USB base station: supports base firmware update via USB without the need of STLink programmer
 * bootloader code for moyoECG device: supports firmware update via radio (requires base with new firmware, old base firmware doesn't support this function)

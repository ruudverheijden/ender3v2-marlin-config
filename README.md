# Marlin Config for my Creality Ender 3 V2

I've flashed my Creality Ender V2 3D Printer with the great fantastic [Marlin Firmware]([https://link](https://marlinfw.org/)). This repo hosts the config files that I use to build the firmware.

Note: this config is specifically customized based on the mods that I've done to my Creality Ender 3 V2, so it may not work for your 3D printer.

## Source

The config is based on the [example configuration published by Marlin](https://github.com/MarlinFirmware/Configurations/tree/import-2.0.x/config/examples/Creality/Ender-3%20V2) for the 2.0.x versions.

## How to build

1. Download the latest version of Marlin for their [Github repo](https://github.com/MarlinFirmware/Marlin)
2. Install VSCode with the ["PlatformIO IDE" plugin](https://platformio.org/install/ide?install=vscode) and ["Auto Build Marlin" plugin](https://marlinfw.org/docs/basics/auto_build_marlin.html)
3. Copy the config files from this repo to the `/Marlin/` folder
4. Open the project root folder in VSCode, click the Auto Build Marlin icon on the left toolbar and hit "Show ABM Panel"
5. Use the ABM panel to Build the firmware

## How to update

1. Download the latest version of Marlin for their [Github repo](https://github.com/MarlinFirmware/Marlin)
2. Download the Ender3 V2 [configuration files matching the new Marlin version](https://github.com/MarlinFirmware/Configurations)
3. Merge all earlier made modifications (commented with "AANGEPAST") into the new configuration files
4. Build the firmware
# Where to get firmware

gerefi firmware releases are located [here](https://github.com/gerefi/ecu-fw/releases). You can download a release and install to the ECU with the console, or another way is to use TunerStudio (TS).

## Tuner Studio Setup

Make sure that you have downloaded the latest version of TunerStudio (TS) from [here](https://www.tunerstudio.com/index.php/tuner-studio). Although the base version of the software is free, it is strongly recommended to buy a license for the additional features including auto-tuning and the ability to customize the default dashboard.

Begin the setup by plugging the ECU into the laptop and opening TS. Create a new project and click _detect_ under firmware. Select the COM port corresponding to the gerefi ECU in the device list. If the COM port cannot be found or the firmware cannot be automatically detected, click _Other/Browse_ and load the .ini file for the ECU which can either be downloaded or found within the ZIP file on the USB device which appears when the ECU is plugged into the computer.

## Note

As per the [gerefi Statement](https://www.ecu.tech/announcements), we want to make clear that gerefi is currently a fork of rusEFI, and that present boards are BOTH rusEFI and gerefi compatible. As time goes on, and more changes are made, this compatibility may change.

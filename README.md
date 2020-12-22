# Blinking

## Devices

LAUNCHXL-CC1352R1

## Description

Creation of an app that turn a built-in LED on/off at random intervals for a random time from 1 to 10 seconds.

## Requirements and dependencies

You need install:

1. Code Composted Studio(select SimpleLink CC13xx and CC26xx Wireless MCUs and Spectrum DigitalDebug Probes and Boards -
https://www.ti.com/tool/download/CCSTUDIO
2. Unit Flash - https://www.ti.com/tool/download/UNIFLASH

After installation, CodeComposerStudio will be available for you in/Applications/tidirectory.
After installation, UniFlash will be available for you in/Applications/tidirectory.
In Resource Explorer, install the latest SDK version for CC1352.

## Building the program

1. Download/Clone the source code. 
2. Open CodeComposerStudio.
3. Build the program (empty.c).
4. Connect device.
5. Open UnitFlash program and find device.
6. In UnitFlash (find button Program) -> Flash Image -> Browse -> empty_CC1352R1_LAUNCHXL_tirtos_ccs (dir) -> Debug (dir) -> choose
empty_CC1352R1_LAUNCHXL_tirtos_ccs.out(file).
7. In UnitFlash Load Image
8. Well Done! Your device is blinkig.

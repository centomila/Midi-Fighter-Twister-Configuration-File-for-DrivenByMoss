<!-- TOC -->

- [What is this](#what-is-this)
- [File in this repository](#file-in-this-repository)
- [Prerequisites](#prerequisites)
    - [Tested with](#tested-with)
- [Installation](#installation)
    - [How to load the MF Twister Config file](#how-to-load-the-mf-twister-config-file)
    - [How to load the Bitwig Flexi Configuration File](#how-to-load-the-bitwig-flexi-configuration-file)
- [Usage](#usage)
- [Side Buttons](#side-buttons)
    - [Left Side | Device and Mixer](#left-side--device-and-mixer)
    - [Right Side | EQ+](#right-side--eq)
- [Bank 1 | Selected Track and Selcted Device Control](#bank-1--selected-track-and-selcted-device-control)
- [Bank 2 | EQ+ Band 1-4](#bank-2--eq-band-1-4)
- [Bank 3 | EQ+ Band 5-8](#bank-3--eq-band-5-8)
- [Bank 4 | Track and Mixer Control Volume/Mute](#bank-4--track-and-mixer-control-volumemute)
- [Buy me a coffee](#buy-me-a-coffee)
- [The MIT License MIT](#the-mit-license-mit)

<!-- /TOC -->

## What is this
This is a configuration file for the extension _DrivenByMoss_ to use the Midi Fighter Twister by DjTechTools with Bitwig Studio.

## File in this repository

- MF Twister Flexi Script.md | This file
- centomila-MfTwisterFlexi-V1.0.mfs | MF Twister Config File
- centomila-MfTwisterFlexi-V1.0.properties | Bitwig Flexi Configuration File
- Midi Fighter Twister Flexi.ai | Illustrator Images for this documentation
- centomila-MfTwister.zip | All files in this repository except for the AI file

## Prerequisites
- [Bitwig Studio](https://www.bitwig.com)
- [DJTT Midi Fighter Twister](https://www.midifighter.com/#Twister)
- DJTT MidiFighter Utility
    - [Download for WINDOWS (Official Repository on AWS)](https://s3.amazonaws.com/djtt-utility/mf_utility_installers/Midi+Fighter+Utility+Win.exe) 
    - [Download for MAC (Official Repository on AWS)](https://s3.amazonaws.com/djtt-utility/mf_utility_installers/Midi_Fighter_Utility_OSX.dmg)
- [DrivenByMoss for Bitwig Studio extension](https://mossgrabers.de/Software/Bitwig/Bitwig.html)

### Tested with
- Windows 11 Professional 64-bit
- Bitwig Studio 4.4.0
- Midi Fighter Utility 2.8.5 (Firmware 02 October 2019)

## Installation
### How to load the MF Twister Config file
Before proceeding, close Bitwig Studio or any other software that uses the Midi Fighter Twister MIDI port.
1. Open the DJTT MidiFighter Utility.
    - On Windows search for _MF Utility_ in the start menu. If the installation doesn't generate a shortcut, the application is located in _C:\Program Files\DJTechTools\Midi Fighter Utility._
2. Click on _File_ > _Import Settings_.
3. Load the file _centomila-MfTwisterFlexi-V1.0.mfs_.
4. Press _SEND TO MIDIFIGHTER_ to transfer the configuration to the device.
5. When the transfer has been completed **close the DJTT MidiFighter Utility.**

### How to load the Bitwig Flexi Configuration File
This configuration file requires the [DrivenByMoss for Bitwig Studio Extension](https://mossgrabers.de/Software/Bitwig/Bitwig.html). After installing the extension, open Bitwig Studio and follow the steps below:

1. Open Bitwig Studio.
2. From the Bitwig's Dashboard go to _Preferences_ > _Controllers_.
3. Press _+Add Controller_ and select Generic > Flexi > Press _ADD_
4. Select _Midi Fighter Twister_ from the list of MIDI device for both the ports.
5. In the Load/Save section, press the _Load_ button and select the file _centomila-MfTwisterFlexi-V1.0.properties_.

## Usage
## Side Buttons
Use side buttons to change Banks.
### Left Side | Device and Mixer
- Bank 1 | Selected Track and Selected Device Control
- Cycle Banks (1-4)
- Bank 4 | Track and Mixer Control (Volume/Mute)
### Right Side | EQ+
- Bank 2 | EQ Control (Band 1-4)
- Cycle Banks (1-4)
- Bank 3 | EQ Control (Band 5-8)

## Bank 1 | Selected Track and Selcted Device Control
- Volume/Pan/Mute/Solo/Send FXs encoders and buttons (Line 1) are mapped to the selected track or the _current pinned track_.
- Device encoders (Line 3-4) and buttons are mapped to the selected device or the _current pinned device_.


![Bank 1](PNG/Bank%201.png)

---

## Bank 2 | EQ+ (Band 1-4)
![Bank 2](PNG/Bank%202%20EQ%201-4.png)

---

## Bank 3 | EQ+ (Band 5-8)
![Bank 3](PNG/Bank%203%20EQ%205-8.png)

---

## Bank 4 | Track and Mixer Control (Volume/Mute)
![Bank 4](PNG/Bank%204.png)


## Buy me a coffee
If you like this configuration file, you can buy me a coffee. Thank you! 💖

<a href="https://www.buymeacoffee.com/centomila" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## The MIT License (MIT)
Copyright © 2022 <centomila>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
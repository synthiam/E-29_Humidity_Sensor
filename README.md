# E-29 Humidity Sensor

**Project Status:** Prototype

If you are new to GitHub and would like to create a derivative of this project, please have a look at GitHub instructions to [fork a repo](https://help.github.com/en/articles/fork-a-repo)

## Description

Out of our passion to solve the issue of time waste in the robot creation process, EZ-Builder was born. The EZ-Builder software platform reduces the time it takes to get from idea to implementation. Since 2011 we have been listening to the challenges robot builders encounter and continue to provide them with an ever expanding toolbox of solutions. Join us on this journey!

We didn't stop at the software, we also made time saving hardware solutions. This Humidity sensor reference design is one of them. This sensor is used to measure Realtive Humidity (in percent) and Temperature (in degrees Celcius) with high accuracy. A unique feature of this sensor is that it takes the digital readout from the HDC1080 and converts it to analog so that it can easily be read by a variety of microcontroller boards. It also has an on-board select button, along with RGB LED mode indicator, to allow the output reading for either Humidity or Temperature to be selected. We want to share these files with you so you can create your own version for your community and customers to enjoy!

**Features:**
- Analog output
- RGB Status LED
- Humidity/Temp Mode Button
- PIC programming port
- 3.3V voltage regualtor on-board
- Voltage requirement: 3.2-16V (3.3V typical)
- Current draw: 415mA
- Dimensions: 27.3(W) x 39.4(L) x 7.5(H) (mm)
- Weight: 3g

**Major components:** 
- PIC16F1704-I/ST PIC Microcontroller (custom firmware provided)
- SPX3819M5-L-3-3/TR 3.3V Regulator

**Manufacturing notes:** 
1. Supplier: programs custom firmware into the PIC16F1704-I/ST at their facility before sending to manufacturer
2. Manufacturer: Single side placement and soldering of SMT components

## Contents

[**Documentation:**](https://github.com/synthiam/E-29_Humidity_Sensor/tree/master/E-29%20Documentation) Schematic PDF, Datasheet PDF, BOM

[**Hardware:**](https://github.com/synthiam/E-29_Humidity_Sensor/tree/master/E-29%20Hardware) Altium PCB design File, Altium SCH Design File

[**Firmware:**](https://github.com/synthiam/E-29_Humidity_Sensor/tree/master/E-29%20Firmware) Code, Compiled Hex

*Altium Libraries are also available <a href="https://github.com/synthiam/Synthiam_Altium_Librairies">here</a>*

## Photos

<p align="left">
<img src="https://live.staticflickr.com/65535/47691863052_5396ef24e6_k.jpg" width="683" height="383">
<img src="https://live.staticflickr.com/65535/32801180607_e4eb735d66_k.jpg" width="683" height="383"></p>

## Contact

For profit use of these files requires written consent. Contact partners@synthiam.com. For everyone else, party on!

Synthiam Website: https://synthiam.com

## License

This project is released under the following licenses:

**Hardware:** Creative Commons Plus Attribution-NonCommercial 4.0 International (CC+ BY-NC 4.0)

**Firmware:** Apache 2.0 + “Commons Clause” License Condition v1.0

Please see [LICENSE.md](https://github.com/synthiam/E-29_Humidity_Sensor/blob/master/LICENSE.md) for license details.

<a href="https://synthiam.com"><img src="https://live.staticflickr.com/65535/47791527651_358dffb302_m.jpg"></a>

TLC5940Driver
=============
Introduction
============
The TLC5940Driver is a development board can be used to investigate the capabilities of upto 3 TLC5940 LED driver chips using an Atmel ATMEGA88

![tlc5940driverbrd](https://cloud.githubusercontent.com/assets/5130298/7216062/eb26d70c-e5e8-11e4-9456-1a7475dc4c6c.PNG)

Features
========
1. Reprogrammable ATMEGA88 microcontroller
2. Upto 3 TLC5940 LED drivers
3. Dimming control switch inputs
4. Soft latching power ON/OFF
5. Demo HEX file to fade 16 LEDs (TLC5940Driver-1xTLC5940.hex)
6. Demo HEX file to fade 48 LEDs (TLC5940Driver-3xTLC5940.hex)

Licence
=======
<p>This work is licensed under a <a href="http://www.creativecommons.org/licenses/by-sa/3.0" target="_blank">Creative Commons Attribution-ShareAlike 3.0 Unported License</a> 

Schematic
=========
![tlc5940driversch](https://cloud.githubusercontent.com/assets/5130298/7105189/1923fe66-e105-11e4-80e8-40ed838f922f.PNG)

LEDPlate
========
![ledplate](https://cloud.githubusercontent.com/assets/5130298/7105035/c409c99a-e0fc-11e4-9680-42f8ffbcb5a7.PNG)

Programming File Fuse Settings - ATMEGA88 
=========================================
Set fuses before flashing program code

1. BOOTSZ: 1024W_0C00
2. SPIEN: tick
3. EESAVE: tick
4. BODLEVEL: DISABLED
5. CKOUT: tick
6. SUT_CKSEL: INTROSC_8MHZ_6CK_14CK_65MS
7. EXT:  F9
8. HIGH: D7
9. LOW:  A2

# TQFP32 Programmer Shield

This repository contains the Eagle files containing the schematic and PCB board design for a custom designed Arduino Shield. This Arduino Shield is meant to simple be a programmer for the TQFP32 package Atmega328PAU chips. The TQFP32 to DIP adapters are easily found on ebay.

## Bill of Materials:
 * 1x 16Mhz Crystal
 * 2x strips of .1" pitch male headers
 * 2x strips of .1" pitch female headers
 * 2x 22pF ceramic caps
 * 1x 220 ohm resistor
 * 1x TQFP32 to DIP adapter

## Pictures:
 * ![Plain PCB](https://github.com/atucom/TQFP32ProgrammerShield/blob/master/Plain_PCB.JPG)
 * ![Soldered Components](https://github.com/atucom/TQFP32ProgrammerShield/blob/master/Soldered.JPG)
 * ![Fully Assembled](https://github.com/atucom/TQFP32ProgrammerShield/blob/master/Fully_Assembled.JPG)

## Programming:
Programming the inserted TQFP32 Atmega is the same as programming any other non flashed single chip.
 * Flash your Arduino Uno with the ArduinoISP sketch
 * Upload your actual sketch using Sketch > Upload Using Programmer

---
title: Schematic
---
# HMI Subsystem

![Schematic](Revision%202%20Schematic_page-0001.jpg)

This schematic is my first revision for an OLED HMI subsystem. Design choices regarding the microcontroller were made according to the [ESP 32 datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3-wroom-1_wroom-1u_datasheet_en.pdf). On page 42, there is a section describing what basic peripherals should look like. This included the EN and Boot functions that the board provides. A descrption of each section will be provided bellow.

The Human Interface is a joystick like button that allows users to scroll up, down, and selected on the OLED screen. The header pins are used to connect to an OLED screen because there are close to no options for an OLED surface mount system. The daisy chain layout is there to provide back and forth communication for all subsystems. The system can also be powered via the daisy chain and also pass the power along it. Speaking of power, the 3.3v switching regulator mirror is datasheet schematic. It also is recommended that a power supply 4.75v to 40v is selected to insure the the board will always function..<br>

All parts at the time of making the schematic, are able to be bought off of Digikey. Links to the Packed Altium Project and PDF Schematics are below. <br>

[PDF](Final%20Schematic.pdf) <br>
[Zip](X.Heafey_HMI_Subsystem%20(4-17-2025%204-51-30%20PM).zip)

# PCB Layers

![TopLayer](Top%20layer-1.png)
![BottomLayer](Screenshot%202025-04-17%20164459.png)
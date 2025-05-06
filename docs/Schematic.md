---
title: Schematic
---
# HMI Subsystem

![Schematic](Final%20Schematic-1.png)

This schematic is my final revision for an OLED HMI subsystem. Design choices regarding the microcontroller were made according to the [ESP 32 datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3-wroom-1_wroom-1u_datasheet_en.pdf). On page 42, there is a section describing what basic peripherals should look like. This included the EN and Boot functions that the board provides. A descrption of each section will be provided bellow.

The Human Interface is a joystick like button that allows users to scroll up, down, and selected on the OLED screen. The header pins are used to connect to an OLED screen because there are next to no options for an OLED surface mount system. The daisy chain layout is there to provide back and forth communication for all subsystems. The system can also be powered via the daisy chain and also pass the power along it. Speaking of power, the 3.3v switching regulator mirror is datasheet schematic. It also is recommended that a power supply 4.75v to 40v is selected to insure the the board will always function.<br>

All parts at the time of making the schematic, are able to be bought off of Digikey. Links to the Packed Altium Project and PDF Schematics are below. <br>

[PDF](Final%20Schematic.pdf) <br>
[Zip](X.Heafey_HMI_Subsystem%20(4-17-2025%204-51-30%20PM).zip)

# PCB Layers

![TopLayer](Top%20layer-1.png)
![BottomLayer](Screenshot%202025-04-17%20164459.png)

Gerber Files for JLC manufacturing<br>
![Zip](Gerber%20and%20Drill.zip)

## Team PCB Layers

Sara's board<br>
![SB Front](SB%20Front.png)
![SB Back](SB%20Back.png)

Julia's board<br>
![JS Front](JS%20Front.png)
![JS Back](JS%20Back.png)

Ella's board<br>
![EG Front](ella_top.png)
![EG Back](ella_bottom.png)


# Team System 

This is my teams project. It is a centrifuge gravity simulator. If a user is far away enough from the motor, they can select a planet and the centrifuge will spin at different speed depending on selection. The user can also spin the motor in a different direction and see sensor data. A distance sensor is used to make sure the user is away from the spinning parts. The motor data will also be sent over wifi.<br>

With this system a user will be able to control the speed of the centrifuge using the joystick and a screen. When the user selects an option, a message will be sent to another system controling the motor, simulating planent gravity. Distance data can be seen as well to tell the user to get further from the motor when on. This distance data will be sent from another system. This lets a user do everything they could want with our project and meets product requirements for sending and reciving data, and being a usable human interface. <br>

# Bill of Materials 

![BOM](Final%20BOM-1.png)
[PDF](Final%20BOM.pdf)<br>

Above is my bill of materials. The initial OLED screen I choose was just to expensive. Therefore I selected a version that we would be using in class so that I would not have to purchase it. A pdf was provided so that you could click on the links. Also the datasheets for each component can be downloaded in the link below.<br>

[Datasheets](Datasheets.zip)<br>

# Final Thoughts

If I had to create a second version, there would be several things I would change. The first change I would include is header pins for every pin on my ESP-32. This would allow for better debugging on my end. I would have a seperate header for the ability to use SPI communication. I would also attach SPI communication to the daisy chain headers as well. I would have jumpers in series with that connection to enable or disable SPI communication manually. This would allow for the option of faster SPI communcation bettween boards, fixing the inconvence of speed my team has. Manual jumpers would also be in series with Vin of the daisy chain headers, the barrel jack, and the input of the switching regulator to make sure that swaping is simple and convienent. Lastly all headers and pins should be label with text to make placement of parts and pin identification easier.<br>
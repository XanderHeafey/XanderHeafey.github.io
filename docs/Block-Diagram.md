---
title: Block Diagram
---

![Block Diagram](Final%20Block%20Diagram.png)

This block diagram was made to fulfill the need for a human interface for my teams project. None of the part numbers have been selected due to not choosing parts as of yet. This system is designed to display a planet to the user and then with a series of inputs, would be able to see the equivalent gravity of said planet. Also the units for the planets gravity would change with an input. More information about my teams subsystem can be found [here](https://egr314-2025-s-301.github.io/).<br>

# Decision Making Process

After many iterations, the final block diagram for my subsystem is completed. To power the esp32 chip, there is the option of using power from the ribbon cables, micro USB B connector and/or a wall power supply. These are all feed into a switching regulator that produces 3.3v for the output. The switching regulator powers the esp32. The joystick is what a user would use to control the oled screen. The oled uses i2c communication with my system as well. Ribbon cable connectors allow connections and communcation with other subsystems. That is why the ribbon cable is also connected to the esp32's rx and tx pins.<br>

With this setup, all requirements for team project can be meet. My system can display any text and send any message based on an input. My system can also recive any message and print it on the screen. Because there are three lines to the esp32 from the joystick, on a screen, a user is able to scroll up, down, and selected options displayed. This create a complete Human Interface.
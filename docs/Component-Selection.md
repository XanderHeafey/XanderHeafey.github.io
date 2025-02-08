---
title: Component Selection
---

### 3.3 Switching Regulator
#### Option 1
| Solution | Pros | Cons |
|----------|------|------|
|![LM2575D2T](LM2575D2T-3.3G.jpg) $1.86 per<br> LM2575D2T-3.3G [Link](https://www.digikey.com/en/products/detail/onsemi/LM2575D2T-3-3G/1476686)|1. Experience with this component before<br>2. Fixed<br>3.Easier to surface mount by hand|1. Large Surface mount component| 

#### Option 2
| Solution | Pros | Cons |
|----------|------|------|
|![TPS62152RGTR](TPS62152RGTR.JPG) $1.42 per<br> TPS62152RGTR [Link](https://www.digikey.com/en/products/detail/texas-instruments/TPS62152RGTR/2833441)|1. Takes less space on pcb<br>2. Cheapest component<br>3. Fixed|1. Harder to surface mount due to size and pin orientation.<br>2. More components on for recommended circuit.|

#### Option 3
| Solution | Pros | Cons |
|----------|------|------|
|![LM3671MF-3.3/NOPB](LM3671MF-3.3-NOPB.JPG) $1.56 per<br> LM3671MF-3.3/NOPB [Link](https://www.digikey.com/en/products/detail/texas-instruments/LM3671MF-3-3-NOPB/1590062)|1. Smallest component<br>2. Surface mounting easier due to pin orientation.|1. Input voltage is only from 3-5.5v<br>2. Max current out is 500mA (Might not be a con depending on what other components I select)|

#### Selection

I am choosing option 1 or The LM2575D2T because of its ease to surface mount and also the fact that I have made circuits with this component before. I do not believe that its size will be a problem in the construction of my subsystem as of right now. Also it could easily connect to different power supplies based off the input voltage variance given in the data sheet. 

### OLED Screen
#### Option 1
| Solution | Pros | Cons |
|----------|------|------|
|![MDOB128064V2V-WI](MDOB128064V2V-WI.jpg) $22.06 Ext Price<br> MDOB128064V2V-WI [Link](https://www.digikey.com/en/products/detail/midas-displays/MDOB128064V2V-WI/20841734)|1. Simple layout<br>2. Easy to wire<br>3. Initialization code in the datasheet|1. Can only buy in quantities of 2|

#### Option 2
| Solution | Pros | Cons |
|----------|------|------|
|![AOM12864A0-0.96WW-ANO](MFG_AOM12864A0-0.96WW-ANO.png) $11.25 per<br> AOM12864A0-0.96WW-ANO [Link](https://www.digikey.com/en/products/detail/orient-display/AOM12864A0-0-96WW-ANO/22531926)|1. Simple data sheet<br>2. Cheaper price|1. Only monochrome white<br>2. SPI communication meaning more inputs|

#### Option 3
| Solution | Pros | Cons |
|----------|------|------|
|![NHD-1.8-160128UBC3](NHD-1.8-160128UBC3.jpg) $25.91 per<br> NHD-1.8-160128UBC3 [Link](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-1-8-160128UBC3/23334148)|1. Bigger screen<br>2. RGB customization|1. Extra layers of complexity due to its 20 connections.<br>2. Most expensive.|

#### Selection

I will be choosing option 1. The MDOB128064V2V-WI comes with two screens at the price of $22.06. Although the screens are small, it would be possible to have two screens instead of one for my block diagram. One screen could display a planet and the other would be able to display the planets info. Also, having two screen may make it easier to view sensor data and turn of GPIO pins. 

### Input Interface
#### Option 1
| Solution | Pros | Cons |
|----------|------|------|
|![JS1300AQ](JS1300AQ.jpg) $2.18 per<br> JS1300AQ [Link](https://www.digikey.com/en/products/detail/e-switch/JS1300AQ/1556576)|1. Conveniently packaged<br>2. Simple data sheet|1. Price relative to other pushbuttons<br>2. Might press buttons on accident|

#### Option 2
| Solution | Pros | Cons |
|----------|------|------|
|
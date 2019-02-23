# Homebrewing PCBs
This is a collection of Gerber files for PCBs I've created for homebrewing applications. Use at your own risk. Please share any issues you may have, or any modifications of these you make. Cheers!

## ESP8266 homebrewing board
### Purpose
This PCB was created for use with [thorrak](https://github.com/thorrak/)'s [ESP8266 based BrewPi Implementation](https://github.com/thorrak/brewpi-esp8266).

### Bill of Materials
|Qty|Description|Details|Source|
|---|------------------------|--------------|--------------|
|1  |ESP8266 Homebrewing PCB|  |[pcbway](https://www.pcbway.com/project/shareproject/ESP8266_Homebrew_v0_1_3.html)|
|2  |0.1μF 25v capacitor|0805|Digikey 399-1168-1-ND|
|2  |NPN transistor|SOT23-3|Digikey TMBT3904LMCT-ND|
|2  |N-channel MOSFET|SOT23-3|Digikey BSS138-FDICT-ND|
|4  |10kΩ SMD resistor   |5%/0.25W/0603|Digikey RHM10KDCT-ND|
|2  |1kΩ SMD resistor   |5%/0.25W/0603|Digikey RHM1.0KDCT-ND|
|1  |3.3kΩ SMD resistor   |5%/0.25W/0603|Digikey RHM3.3KDCT-ND|
|6  |2 position terminal blocks |2.54mm|Digikey A98333-ND|
|1  |Breakable header|2.54mm|Digikey 3M156850-36-ND|

### Acknowledgements
day_trippr from homebrewtalk provided significant guidance on PCB design. Thanks also to thorrak, and bigdaddyale from homebrewtalk.

## Raspberry Pi homebrewing board
### Purpose
This PCB was created for use with:
* [Node-RED](https://nodered.org) IoT Software
* [Manuel83](https://github.com/Manuel83)'s [CraftBeerPi](https://github.com/Manuel83/craftbeerpi3)
* [DougEdey](https://github.com/DougEdey/)'s [Strangebrew Elsinore](https://github.com/DougEdey/SB_Elsinore_Server)
* [andrewerrington](https://github.com/andrewerrington)'s [fuscus](https://github.com/andrewerrington/fuscus)
* And others!

### Bill of Materials
|Qty|Description|Details|Source|
|---|------------------------|--------------|--------------|
|1  |Raspberry Pi Homebrewing PCB|   |[pcbway](https://www.pcbway.com/project/shareproject/Raspberry_Pi_Homebrew_board_v0_2_2.html)|
|1  |ULN2803A Darlington array|DIP|Digikey 497-2356-5-ND|
|12 |2 position terminal blocks |2.54mm|Digikey A98333-ND|
|1  |0.1μF 25v capacitor|0805|Digikey 399-1168-1-ND|
|1  |3.3kΩ resistor |5%/0.25W/0603|Digikey RHM3.3KDCT-ND|
|1  |Raspberry Pi stacking header |2.54mm|Digikey 1528-1385-ND|

### Acknowledgements
Jake Mrillies from the CraftBeerPi User Group found errors with an initial version of this board and provided other valuable feedback.

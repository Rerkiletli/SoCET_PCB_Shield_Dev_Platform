Grade: 63/100%

Schematic: 43/70%
PCB: 20/30%


----- Schematic -----

Power Supply: 15/15%

Notes: NA 


Main IC: 20/30%

Notes: 

* Swap SDO and SDI, you have misconnected them.

Routing: 5/15%

Notes: 

* SPI pins are not connected, use IO.SDI instead of IO{SDI}


Testing Capabilities: 3/5%

Notes: 

* Add an LED for PSU 3.3V.


Neatness: 0/5%

Notes:

* Use hierarchical sheets.
* Add borders for LDO and ADXL343.

--------------------


----- PCB -----

You are supposed to add your PCB into Shield_Pins.kicad_pcb. Delete the one you have created, add it into the original file. Also, there should be only 1 project present in your folder, you have created a project for magnetometer, don't create a new one, use the Shield_Pins as your project file. 

Component Placing: 10/10%

Notes: NA


Layers and Grounding: 10/10%

Notes: NA


Routing: 0/10%

Notes:

* SPI pins are not connected, when you fix the issue mentioned above, this also will be fixed.

--------------------


SCHEMATIC Power Supply --> Power supply design.
SCHEMATIC Main IC --> Main IC and the necessities (Decoupling Caps, Power Pins, etc...).
SCHEMATIC Routing --> Global label placement.
SCHEMATIC Testing Capabilities --> Testing LEDs and such physical responses or testing pins.
SCHEMATIC Neatness --> How clear and indicative your design is.

PCB Component Placing --> Placement of the components on PCB to achieve the easiest routings.
PCB Layers and Grounding --> Ground layers used and general grounding of the PCB.
Routing 
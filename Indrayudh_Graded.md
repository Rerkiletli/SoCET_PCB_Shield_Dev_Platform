Grade: 58/100%

Schematic: 48/70%
PCB: 10/30%


----- Schematic -----

Power Supply: 15/15%

Notes: NA


Main IC: 10/30%

Notes: 

* RSTN and INTN requires pull-up resistors.
* Connect PMODEs to GND.
* You can connect SPD_LED and DUP_LED to an external LED but LINK_LED and ACT_LED are supposed to be connected to RJ45 conn.'s pin 11-14.


Routing: 15/15%

Notes: NA


Testing Capabilities: 5/5%

Notes: NA


Neatness: 3/5%

Notes: Include W5500's circuitry in W5500's border.

--------------------


----- PCB -----

Component Placing: 0/10%

Notes:

* You should have the ethernet port to be next to the PCB border.
* Make the PCB 2 layers.


Layers and Grounding: 5/10%

Notes: 

* Add a via for every GND connection.


Routing: 5/10%

Notes:

* Make sure to have better and shorter track lengths for some connections (like IO7).
* Don't create acid traps. (https://www.nextpcb.com/blog/acid-traps)

--------------------


SCHEMATIC Power Supply --> Power supply design.
SCHEMATIC Main IC --> Main IC and the necessities (Decoupling Caps, Power Pins, etc...).
SCHEMATIC Routing --> Global label placement.
SCHEMATIC Testing Capabilities --> Testing LEDs and such physical responses or testing pins.
SCHEMATIC Neatness --> How clear and indicative your design is.

PCB Component Placing --> Placement of the components on PCB to achieve the easiest routings.
PCB Layers and Grounding --> Ground layers used and general grounding of the PCB.
Routing 
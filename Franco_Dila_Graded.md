Grade: 79/100%

Schematic: 53/70%
PCB: 26/30%


----- Schematic -----

Power Supply: 15/15%

Notes: NA


Main IC: 25/30%

Notes: Missing decoupling capacitors for VCC_IO and VCC pins.


Routing: 5/15%

Notes: Check the ERC errors, no need to add 3.3V_LED, LED_SP, or VCC_VCC-IO global labels, you can just use 3.3V power flag instead.


Testing Capabilities: 3/5%

Notes: Used the wrong transistor. It should be a NPN transistor such as 2N2222 or 2N2219 with SOT-23 footprint. Also you forgot to connect one of the LEDs of the transistor.


Neatness: 5/5%

Notes: NA

--------------------


----- PCB -----

Component Placing: 8/10%

Notes: Why place one of the transistors to left side and other to right side, you can just place both of them to right side where the RX and TX is located? Also, no need to put everything so close to each other, try to use the whole PCB.


Layers and Grounding: 10/10%

Notes: NA


Routing: 8/10%

Notes: Please increase the width of the 5V+ and other power pins. 

--------------------


SCHEMATIC Power Supply --> Power supply design.
SCHEMATIC Main IC --> Main IC and the necessities (Decoupling Caps, Power Pins, etc...).
SCHEMATIC Routing --> Global label placement.
SCHEMATIC Testing Capabilities --> Testing LEDs and such physical responses or testing pins.
SCHEMATIC Neatness --> How clear and indicative your design is.

PCB Component Placing --> Placement of the components on PCB to achieve the easiest routings.
PCB Layers and Grounding --> Ground layers used and general grounding of the PCB.
Routing 
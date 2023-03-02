Grade: 83

Schematic: 58/70%
PCB: 25/30%



----- Schematic -----

Power Supply: 15/15%

Notes: NA


Main IC: 30/30%

Notes: NA


Routing: 5/15%

Notes: Having global labels as IO 5 is confusing, instead of IO 5, you can use ESP-IO5 as a global label. Also, you should be using +3.3V instead of 3V3 global label.


Testing Capabilities: 4/5%

Notes: For power indicators such as +3.3V you don't have to use a transistor. Just connect the +3.3V directly into the LED.


Neatness: 4/5%

Notes: J10 could be separated into a different part, see me for more details.

--------------------


----- PCB -----

Component Placing: 10/10%

Notes: NA


Layers and Grounding: 10/10%

Notes: NA


Routing: 5/10%

Notes: Increase the length for the power (+3.3V and +5V) connections. Complete the whole routing process, there are floating pins and if you can't find it, see me.

--------------------


SCHEMATIC Power Supply --> Power supply design.
SCHEMATIC Main IC --> Main IC and the necessities (Decoupling Caps, Power Pins, etc...).
SCHEMATIC Routing --> Global label placement.
SCHEMATIC Testing Capabilities --> Testing LEDs and such physical responses or testing pins.
SCHEMATIC Neatness --> How clear and indicative your design is.

PCB Component Placing --> Placement of the components on PCB to achieve the easiest routings.
PCB Layers and Grounding --> Ground layers used and general grounding of the PCB.
Routing 
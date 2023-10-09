Grade: 65/100%

Schematic: 60/70%
PCB: 5/30%


----- Schematic -----

Please annotate the schematic and check ERC.

Power Supply: 15/15%

Notes: NA 


Main IC: 30/30%

Notes: NA


Routing: 10/15%

Notes: Don't use 3.3V global label, just use the power label +3.3V.


Testing Capabilities: 5/5%

Notes: NA


Neatness: 0/5%

Notes: You did used hierarchical sheet correctly but please remove your old design.

--------------------


----- PCB -----

Please check DRC.

Component Placing: 0/10%

Notes: 

* Decoupling capacitors are supposed to be closer to each other. 
* Place the components so that you don't have long tracks.
* Create groups for the main IC and the PSU, your design looks really scattered around.


Layers and Grounding: 5/10%

Notes: Add GND via for all the SMD GND pads.


Routing: 0/10%

Notes: Please complete the power connections such as 3.3V and 5.0V connection. 



--------------------


SCHEMATIC Power Supply --> Power supply design.
SCHEMATIC Main IC --> Main IC and the necessities (Decoupling Caps, Power Pins, etc...).
SCHEMATIC Routing --> Global label placement.
SCHEMATIC Testing Capabilities --> Testing LEDs and such physical responses or testing pins.
SCHEMATIC Neatness --> How clear and indicative your design is.

PCB Component Placing --> Placement of the components on PCB to achieve the easiest routings.
PCB Layers and Grounding --> Ground layers used and general grounding of the PCB.
Routing 
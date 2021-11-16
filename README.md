This cat feeder is a remix to add functionality. 

It uses 3 feeders, each with an RFID reader to read each cats collar tag. Each dispenser has its own auger based dispenser powered by a NEMA17 stepper motor. The RFID readers and steppers are controlled by an arduino uno and an esp8266 (D1 Mini). Two motor shield V2s are used to actually control the motors. All power is supplied by a 5v adapter. The electronics all sit in between the 3 vertical PVC tubes (3" PVC). 

The two horizontal pieces holding the PVC and electronics have one pipeholder and 3 clamps. They're then connected with 3 sideplates. 

Each dispenser has the dispenser, 4 legs, one motorplate, both sides of the auger, the bowlstand, the lid, and the lidpipebracket. As it IS, I had to shoot some small screws to hold the lid on and connect the pipeholder to the PVC pipe. I'll fix it later to utilize the same connections as everything else, but the pipeholder was designed to stick to the pipe with plastic epoxy. The bowl stand does need the RFID inlay to be slightly expanded to fit wiring and shrink wrap better. The shrink wrap is designed to keep it water resistant (because the cat slobbers a lot).

Most major connections use 4mm bolts and brass melt in inserts (4mm inserts with 6mm outer diameter). They work really well and are pretty easy to insert, but be sure to make them fit in straight or it'll cause some issues. 

There are currently some minor clogging issues. SO FAR, they've been easy to break free and I think the current iteration has fixed them, but I'm working on a baffle just in case. I'm predicting it'll be needed if the feed towers are ever full.

Code:
https://github.com/jt20110627/catfeeder


Full Parts List (non-3d printed):
5v power input:
https://www.amazon.com/gp/product/B078RZBL8X/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1

MotorShieldV2 (2 of them):
https://www.amazon.com/gp/product/B073SP76MC/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1

Arduino Uno:
https://www.amazon.com/gp/product/B01EWOE0UU/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1

Auger bolts (3, one in each auger.
https://www.amazon.com/gp/product/B07D5S31W4/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1
Note, each auger has an inlay for a 3mm flat nut that those bolts will screw into. They are press fit. I just got those at lowes.

5v to 3.3V (3, powers each RFID reader):
https://www.amazon.com/gp/product/B07CP4P5XJ/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1
Note, power these with main 5v input NOT arduino 5V pin because the arduino will not reliably supply it.

Screw shield (makes life easier, just one):
https://www.amazon.com/gp/product/B014SGTP20/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1

Wiring (need 7 wires total for each rfid reader, I used red and black twice):
https://www.amazon.com/gp/product/B07G844GCY/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&th=1

M4x8mm:
https://www.amazon.com/gp/product/B01BBOZLQ6/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1

Brass inserts:
https://www.amazon.com/gp/product/B08N9ZCHKG/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1

M4x12mm:
https://www.amazon.com/gp/product/B07MS59H22/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1

D1 mini ESP8266 (only actually need one but theyre fun):
https://www.amazon.com/gp/product/B081PX9YFV/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1

Stepper Motors:
https://www.amazon.com/gp/product/B07Y2SVNGP/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&th=1

RFID Reader: 
https://www.amazon.com/gp/product/B07QBPGYBF/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1

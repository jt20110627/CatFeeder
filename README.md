# CatFeeder
Arduino and ESP8266 code for a 3 bowl RFID catfeeder.

The arduino has 2 MotorShieldV2s with 3 NEMA17 stepper motors. The ESP is a D1mini. 

It also utilizes 3 arduino MFRC type RFID readers. Each is powered by a small 3.3V power supply. This is important as the arduino 3.3V pin can NOT provide enough power for them to function.

The arduino, the shield, and the 5v to 3.3v converters all utilize a 5v input supply. I do use an arduino screw terminal shield on top to easily connect pins from the ESP to the arduino and to connect the 5v input to the arduino.

When connecting the motorshield be sure to remove the VIN jumper (I blew 2 boards and an arduino somehow not doing this so best to be safe).

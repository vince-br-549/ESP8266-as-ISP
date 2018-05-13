# ESP8266
This sketch contains minor changes to the Arduino sketch
that allows one to use an ESP8266 ( Wemos D1 mini in my case) as 
an ISP.

I used it to program ATtiny85
Wiring
Wemos       ATtiny85
SCK (D5) >  pin 7 (SCK)
MISO (D6) > pin 6 (MISO)
MOSI (D7) > pin 5 (MOSI)
D4 	  > pin 1 (RESET)
GND	  > pin 4
3.3v      > pin 8 

To upload a sketch to the ATtiny85.
After installing the ISP sketch,
change the board type to ATtiny85.

Note this assumes you have already installed Arduino IDE support for the ATtiny85



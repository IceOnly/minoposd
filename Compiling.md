# Compiling the source #


How to compile and flash arduino code is documented many times on the web.

A good entry point for how to start with arduino and to compile the code is here: http://arduino.cc/en/Guide/HomePage

A good entry point for how to flash the code is here: http://code.google.com/p/arducam-osd/wiki/Cfg_Update_Firmware

But don't use their hex file of course, but compile the right one for minOPOSD.

The code is here:

http://code.google.com/p/minoposd/source/checkout

And use the 'OSD Config Tool' from my code section trunk/Tools.


Take the libs from master repostiory.

You need Arduino IDE 1.0.1 to compile the Project.
Select "Arduino Nano /w ATmega328" as Board.
Get the hex file from the temp compiling directory (you can see this directory if you enable "Show verbose output during compilation").

The main add-ons to the original code can be found in the files:


UAVTalk.h

UAVTalk.ino

FlightBatt.h

FlightBatt.ino

PacketRxOk.h

PacketRxOk.ino

AnalogRssi.h

AnalogRssi.ino

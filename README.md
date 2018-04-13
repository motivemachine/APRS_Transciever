# APRS_Transciever
An in development design for a complete, standalone transciever for voice and aprs digital communication for the 2meter/70cm band. It is primarily based on the DRA818 radio module and controlled with an arduino. 

This project is made possible for amateur designers like me thanks to the work of:

markqvist and his APRS library:
https://github.com/markqvist/LibAPRS

darksidelemm and his DRA818 serial library:
https://github.com/darksidelemm/dra818

Progress:
Currently the basic Kicad schematic is complete, using an arduino nano and a 74lvc245 to convert the 5v IO to 3.3v for the dRA818V. Resistors on Arduino Nano pins 4-7 form the DDS as used with LibAPRS. No other interfaces are yet included, but many are planned (gps, display, etc.)

Next steps:
After further breadboard testing, complete designs for the PCBs in Kicad. The first design will be for a single-sided PCB for etching at home and further development. A two layer production design will follow after any changes are made

Begin adding some other interfaces to the circuit, such as GPS, sh1106 OLED display, battery management circuits,and other useful telemetry

Firmware will mostly be based on the arduino libraries of others, but will be uploaded here as changes are made. 

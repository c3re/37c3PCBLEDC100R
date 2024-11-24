# 37c3PCBLEDC100R
Coaster for your drinks with option for LED and microcontroller upgrade.
![rendering of the 37c3PCBLEDC100R](https://github.com/c3re/37c3PCBLEDC100R/blob/master/Rev.1/37c3PCBLEDC100R_rendered.png)
## Rev.1
### Electrical connections
Important: Do not power the board by USB and an external power supply at the same time!
The Din pin of the first LED is connected to pin D4 (GPIO2) of the Wemos D1 mini. Two of the mounting holes are connected to GND, two of the holes are connected to 5V. You can use this feature to stack multiple 37c3PCBLEDc100R Boards with brass spacers.
### Bug
The revision 1 contains an error in the PCB-Layout! The error affects all LED footprints, the LED pins 1 & 2 are swapped. To fix the Bug, we recommend to bend pin 2 around the PCB edge and solder it on the bottom to the squared pad.
![rendering of the 37c3PCBLEDC100R](https://github.com/c3re/37c3PCBLEDC100R/blob/master/Rev.1/Bugfix_Rev.1.jpg)
## Rev.2
Bugfixed 
## License
The 37c3 Logo and the dithered image of the bolt cutter were created by Robokid // Luis F. Masallera and Euler Void \
37c3PCBLEDC100R © 2023 by c3RE is licensed under CC BY 4.0. To view a copy of this license, \
visit http://creativecommons.org/licenses/by/4.0/

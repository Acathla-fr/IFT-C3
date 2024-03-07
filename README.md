# IFT-C3
Printed Circuit Board with an ESP32-C3

Erratum: on the silkscreen, pin 20 should be named 20/Rx and pin 21 should be named 21/TX.
The switch cuts the battery from everything else in the circuit. So battery cannot be charged without turning the circuit on.

GPIO 1 is optionnaly used for battery voltage measurement<br/>
GPIO 2 and 3 are optionnaly used for audio<br/>
GPIO 4 is optionnaly used for the light sensor<br/>
GPIO 10 optionnaly used for the RGBW LEDs<br/>
GPIO 9 is plugged to the Boot button which can be used in your design. The reset button cannot.<br/>

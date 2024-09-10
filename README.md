# IFT-C3
Printed Circuit Board with an ESP32-C3. Version 2.1 (2024)

Version released for the new students. Now integrates the support for the OLED screen and the buttons.

BUGS!!! (fixed in the kicad design, not on the produced boards):

    Buttons pinout is wrong, you'll have to solder them rotated 25°. For the Boot/Start button, since I thought there was two buttons in one without verifying, you'll have to be creative to fix it (at least the start button, the boot can be selected with Dupont wires by connecting pin 9 to ground).
    Holes for the screen are too small, you'll have to replace the connector or be creative (file the pins works).

GPIO 0 is used by the keyboard matrix<br/>
GPIO 1 is used by the keyboard matrix and optionnaly for battery voltage measurement<br/>
GPIO 2 and 3 are optionnaly used for audio<br/>
GPIO 4 is optionnaly used for the light sensor or to control the MOSFET<br/>
GPIO 5 is used by the SDA line for the OLED screen<br/>
GPIO 6 is used by the SCL line for the OLED screen<br/>
GPIO 7 is used by the keyboard matrix<br/>
GPIO 8 is used by the keyboard matrix<br/>
GPIO 9 is plugged to the Boot button which can be used in your design. The reset button cannot.<br/>
GPIO 9 also optionnaly used for the RGBW LEDs<br/>
GPIO 10 is used by the keyboard matrix<br/>
GPIO 20 is used by the keyboard matrix but also as the Rx UART
GPIO 21 is used by Tx UART

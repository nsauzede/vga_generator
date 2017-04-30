# VGA Text Color

This project builds upon work in the VGA Text project and does the following:

* Uses Papilio Duo
* Uses LCD wing for Sharp LCD screens (3x6 bits colors)
* Generates horizontal and vertical synchronization signals for a 640x480 VGA-like Sharp LCD screens
* Defines a 8x16 font ROM for ASCII characters 0 to 127
* Defines a buffer of 2x8-bit values use to represent the 80x30 characters on the screen
* Colors can be defined every second byte (VGA-like attributes for foreground/background)

![Papilio Duo + LCD wing on a Sharp LCD screen](duo_lcd_vga.jpg)

## Links

* [Papilio Duo](http://papilio.cc/index.php?n=Papilio.DUOStart)
* [Papilio LCD wing (Sharp LCD screens)](https://www.logre.eu/wiki/Ecran_Sharp_LQ084V1DG21/en)

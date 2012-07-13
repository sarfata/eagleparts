lt3518
======

An eagle library device for the LT3518 (Full-Featured LED Driver with 2.3A Switch Current).

Reference doc: http://www.linear.com/docs/Datasheet/3518fd.pdf

## Packages

The TSSOP16 package is the only one included. This part has an extra pad on the bottom of the chip which must be soldered (it is GND and also helps thermal conduction). Two packages are included which differ by the size of this pad:

* In the first version (EXPOSED-PAD-MINIMAL), the pad follows the minimal recommandation from Linear Technology datasheet
* In the second version (EXPOSED-PAD-LARGE), the pad is made larger than the chip so that you can melt the solder, keep the solder hot and slide the chip in place. This technique was suggested by Michael Hölzl in the 2012 summer edition of Elektor.

## License

"THE BEER-WARE LICENSE" (Revision 42):
<thomas@sarlandie.net> made this stuff. As long as you retain this notice you
can do whatever you want with this it. If we meet some day, and you think
this stuff is worth it, you can buy me a beer in return. Thomas Sarlandie.

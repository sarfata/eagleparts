Eagle Parts
===========

Collection of parts that I have built or gathered from other open-hardware designs.

## Licensing

The parts of this library that were not built by me stay under original license (usually CC-BY or CC-BY-SA).

The parts that I have added are all made available under the CC-BY-SA license: [http://creativecommons.org/licenses/by-sa/2.0/]. You must give attribution in a README file included with the source of your design (and you have to provide source because it's share-alike). Contact me if you would like an exception.

## Parts added by thomas

### LT3518
An eagle library device for the LT3518 (Full-Featured LED Driver with 2.3A Switch Current).

Reference doc: http://www.linear.com/docs/Datasheet/3518fd.pdf

#### Packages

The TSSOP16 package is the only one included. This part has an extra pad on the bottom of the chip which must be soldered (it is GND and also helps thermal conduction). Two packages are included which differ by the size of this pad:

* In the first version (EXPOSED-PAD-MINIMAL), the pad follows the minimal recommandation from Linear Technology datasheet
* In the second version (EXPOSED-PAD-LARGE), the pad is made larger than the chip so that you can melt the solder, keep the solder hot and slide the chip in place. This technique was suggested by Michael Hölzl in the 2012 summer edition of Elektor.

### TC1047

A device for the TC1047 temperature sensor.

### L2020

The L_US device from the standard rcl.lbr file with an added L2020 package.

## Parts gathered from 3rd parties schematics

### RN171

The wifi module. Thanks to seeedstudio Wifi shield: http://www.seeedstudio.com/wiki/Wifi_Shield

### BLE112

The Bluegiga Bluetooth Low Energy module. Thanks to Jeff Rowberg: http://www.inmojo.com/store/jeff-rowberg/item/ble112-bluetooth-low-energy-breakout/

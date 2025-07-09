# SAO Tree Ornament

This board allows you to easily hang and display your SAOs on a tree or other decoration.  It provides power via USB-PB and optionally a small MCU to drive the pins.

## Features

* USB-PD Power entry.  Negotiates for up to <20V@3.25A> (The USB-PD 3.0 65W profile).
* Distributes the high voltage out to other ornaments
* Converts the high voltage down to 3.3V for the SAO
* An MCU can drive the I2C and the GPIO pins if the SAO needs it.

## TODO

* Test and characterize the current capability of the buck converter
* Test that the MCU can be programmed via the TagConnect

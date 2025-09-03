# SAO Tree Ornament

This board allows you to easily hang and display your SAOs on a tree or other decoration.  It provides power via USB-PB and optionally a small MCU to drive the pins.

## Features

* USB-PD Power entry.  Negotiates for up to <20V@3.25A> (The USB-PD 3.0 65W profile).
* Distributes the high voltage out to other ornaments
* Converts the high voltage down to 3.3V for the SAO
* An MCU can drive the I2C and the GPIO pins if the SAO needs it.

## TODO

* Test and characterize the current capability of the buck converter
* Determine source of quiescent current.  Connected 4 ornaments together, and it got into a boot loop.  It also had the Lumen SAO and Debra's floppy arm SAO on there. 

## Next Version Notes

1. Add SOME LEDs to the front of the board to optionally backlight the SAO
2. Add some art to the front of the board
3. Figure out a more efficient counterbalance solution. I underestimated the weight of some of the SAO. A 5mm dowel to bind to the branch might be an option.
4. Might need to move the 2-pin connectors so they don't interfere with the SAO connector.  TBD
5. Reduce 6-pin connector hole sizes. A 0.2mm diameter drop is a good start.  Probably will end up at 0.3mm reduction overall.
6. Maybe add current sensing and feedback out a serial port?
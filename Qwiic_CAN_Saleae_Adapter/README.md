# Qwiic and CAN to Saleae Adapter

## Background

This board is meant to provide a quick (pardon the pun) adapter between I2C and CAN to the Saleae.  Specifically, it provides just enough interface to adapt the signals to something the Saleae can easily handle.

For the I2C side, it provides a standard [QWIIC](https://www.sparkfun.com/qwiic) connection which includes pull up resistors.

For the CAN side, it provides a [transceiver chip](https://www.analog.com/en/products/MAX33040E.html) which will take the differential signal and convert it to single sided. The extra features of the chip aren't used, so they've been disabled.  The power for the chip is provided by the QWIIC connection.  There is a 120 Ohm resistor with a solder jumper to cut in case you want to disable that.

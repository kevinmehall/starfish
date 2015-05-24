This tiny board provides a 12-pin Pmod port, controlled over USB. [Pmod](http://www.digilentinc.com/Pmods/Digilent-Pmod_%20Interface_Specification.pdf) is a standard pinout for SPI, I2C, UART, and GPIO on a 6 or 12 pin connector, with over 100 modules available from several companies. 

Level shifters and a digitally-controlled voltage regulator allow it to operate at 1.2 - 5V IO levels. 

Key components:

  * [Atmel SAMD21](http://www.atmel.com/Images/Atmel-42181-SAM-D21_Datasheet.pdf) - Cortex M0+ microcontroller
  * [Fairchild FXMAR2104](https://www.fairchildsemi.com/datasheets/FX/FXMAR2104.pdf) - IO level shifter

Firmware bringup is in progress. It will work with the [Tessel 2 JavaScript API](https://github.com/tessel/t2-firmware) and [Signalspec](http://signalspec.org).

![alt text](https://github.com/ashandore/3u-module/raw/master/images/board.png "")

3u USB-C STM32G4 microcontroller module. Intended for use with keyboards. It is named for its module connector spacing, which is 57.15mm/2.25in or 3 "standard" key spacings.

## Functionality
- STM32G431CBT6
- SWD debug header with UART tx/rx
- USB 2.0 Type-C
- USB Power Delivery PHY
- USB supply current sensing
- USB supply power switch w/ soft start
- 512kB SPI EEPROM
## Header Connectivity
- 5V - 20V, 3.5A (USB PD)
  - default 5V, 500mA
- 3.3V, 1A
  - current capacity is taken from USB PD rail
- 2x SPI
- 1x UART (no flow control)
- 1x I2C
- 1x GPIO (SPI/UART interface pins can be reconfigured for use as up to 10 additional GPIO)
## Editing
3u was designed in Altium Designer 19. If you would like to use these design files with free software, you can use Altium's CircuitMaker or attempt to import the project into KiCAD using https://github.com/thesourcerer8/altium2kicad. 

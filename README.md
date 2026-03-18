# Kicad-Projects
This repository contains  some 2 layer of PCB module board schematic and layout files designed using kicad software

# BME280 module board
- BME280 module measures pressure, temperature humidity, two mode interface one is I2C and other is SPI so in this design BME280 is interfaced by I2C mode.
- 3.3V DC power supply for operating the board

# DAC module board
- Digital to analog converter using MCP4721 ic
- pull up resistors for i2c  communication protocol SDA and SCL lines
- decoupling capacitor at ouput voltage
- decoupling capacitors at input voltage used MLCC and tantalum as it has low ESR
- 1X5 pin through hole connector to connect the module with controller
-  

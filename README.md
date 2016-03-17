# bescape
Beagle Entertainment System hardware cape files for EAGLE PCB

The BESCape is a BeagleBone Black cape board designed to be used with
the Beagle Entertainment System (http://beaglesnes.org) software system.
BESCape is a hardware interface that provides the BES software with a
DS1307 battery-backed RTC and two Super Nintendo controller connectors. 
This allows a BeagleBone Black running BES to more effectively serve as
a retrogaming console.

The cape uses the following pins:

P8.01: GND       (Grounding plane)
P8.02: GND       (Grounding plane)
P8.26: GPIO1_29  (GPIO for Gamepad2 DATA signal)
P9.01: GND       (Grounding plane)
P9.02: GND       (Grounding plane)
P9.03: VDD_3V3   (3.3VDC to gamepad line-level converter FETs)
P9.04: VDD_3V3   (3.3VDC to RTC and EEPROM)
P9.05: VDD_5V    (5.0VDC to gamepad line-level converter FETs)
P9.06: VDD_5V    (5.0VDC to gamepad line-level converter FETs)
P9.11: UART4_RXD (GPIO for Gamepad1/2 CLOCK signal)
P9.12: GPIO1_28  (GPIO for Gamepad1 DATA signal)
P9.13: UART4_TXD (GPIO for Gamepad1/2 LATCH signal)
P9.17: I2C1_SCL  (I2C SCL for RTC)
P9.18: I2C1_SDA  (I2C SDA for RTC)
P9.19: I2C2_SCL  (I2C SCL for cape EEPROM)
P9.20: I2C2_SDA  (I2C SDA for cape EEPROM)
P9.22: UART2_RXD (GPIO for menu/pause switch signal)
P9.27: GPIO3_19  (GPIO for menu/pause LED)
P9.43: GND       (Grounding plane)
P9.44: GND       (Grounding plane)
P9.45: GND       (Grounding plane)
P9.46: GND       (Grounding plane)
 

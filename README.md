# nPM1300 Module

<p align="center">
  <img src="img/stamp.png" alt="nPM1300 Module" width="300"/>
</p>

## Overview

Compact module integrating Nordic Semiconductor's nPM1300 PMIC with all necessary passive components. Designed for easy integration into Bluetooth Low Energy embedded systems.

## Key Features

- 800 mA battery charger
- Dual 200 mA buck DCDC regulators
- Fuel gauge functionality
- System-level watchdog
- I2C control interface
- USB-C compatible

## Design Resources

- Schematic symbol available
- PCB footprint available

## Requirements for Design

- VSET1 and VSET2 resistors must be provided externally
- VDDIO must be provided externally, but could also be an output from one of your bucks or LDOs on the nPM1300
- If you use the LDOs, please include the recommended decoupling capacitors outside of the stamp.
- I2C pull-ups are required externally
- ESD protection must be provided externally

For detailed specifications, visit [Nordic Semiconductor's nPM1300 page](https://www.nordicsemi.com/Products/nPM1300).

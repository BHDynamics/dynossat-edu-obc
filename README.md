# DynOSSAT-EDU-OBC (On-Board Computer)

**Important note: we have updated the Arduino Boards Manager link.** Please update your Arduino IDE settings with our new link: https://bhdynamics.github.io/board_index/package_bhdynamics_index.json since the previous one (https://bhdynamics.github.io/board_index/package_dynossat_index.json) **NO LONGER WORKS**.

DynOSSAT-EDU is the first open source PocketQube educational kit compatible with CircuitPython and Arduino.

This plaform is equipped with all the necessary modules for the operation of a nanosatellite (PocketQube)
in Low Earth Orbit (LEO) that would serve as a device for teaching, training, and driving curiosity about the philosophy and technology related to NewSpace.

This repository contains the hardware files for the OBC (On-Board Computer), the module responsible for managing the satellite and process sensor data. It
integrates a 9-axis IMU and carries a powerful ATSAMD51.

Hardware in this repository is licenced under **CERN OHL v1.2**.

## Technical details

- Powerful ATSAMD51J20A-AU 120 MHz Cortex-M4F processor with 1 MB flash + 256 KB RAM for all your CircuitPython needs
- 32 Mbit SPI flash for storing CircuitPython code and libraries
- High-precision ICM-20948 Inertial Measurement Unit including Accelerometer, Gyroscope and Magnetometer for Attitude management
- MCP9808 Digital Temperature Sensor
- SGP30 TVOC and eqCO2 air quality sensor
- User-controllable WS2812B addressable RGB LED
- Separate 5V and 3.3V rails, providing up to 1A/500mA respectively
- MicroSD Card slot
- Female USB-C 2.0 connector for power and data logging
- PQBH40 bus exposing 10 digital pins, 6 analog pins (+ true DAC), an I2C bus, an SPI bus and an UART

## Documentation

Available in this repo's [Wiki](https://github.com/BHDynamics/dynossat-edu-obc/wiki).

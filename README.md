# TL; DR

Weather Station (or MeteoStation) is developed as Internet of Things (IoT) device with low-power consumption.

Project is under development. Goals or plans may be changed in the future, while newest repository\`s commit will contain actual information

### Planned:

- Temperature, Humidity, Atmosphere pressure measurement features via AHT10, BMP280.
- OLED Display support for showing results after measurements.
- Error handling for peripherals and LEDs indication (if devices have errors).
- Debugger support and UART Logging.
- Necessary documentation writing for project.
- Optional: PCB creation.

### Technical Specification (Short)
- STM32F401CCU6 is used (Black Pill used, but default board must be supported normally)
- AHT10 sensor for Temperature and Humidity (I2C)
- BMP280 for atmosphere pressure (I2C)
- 0.96" OLED (SSD1315) display (I2C)
- Any UART and Debugger may be used if they satisfy schemes (see docs/), but CH340C and ST-Link (V2 clone) are used for testing.

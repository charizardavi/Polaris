# Polaris Flight Computer

![pcb image](https://raw.githubusercontent.com/charizardavi/Polaris/refs/heads/main/kicad_preview.png)

System clock: 480mhz

Interfaces:
- ST-Link
- USB OTG (type C)
- 5x Servo/BLDC Motor output

currently using:
- STM32H743ZIT6 MCU
- LSM6DSO 6-axis IMU
- BMP388 barometer
- SDMMC interface on MCU to write to micro SD card


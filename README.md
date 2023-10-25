# HMI-Scanner
A multi sensor environment scanner based on the RT-thread x Renesas RA6M3 HMI-Board

[Hardware Showcase Video](https://youtu.be/nxeD5lMJxVE)

Current Progress:
```
GUI - 95%
Code - 95%
3d printed case - 90% 
Custom PCB for sensors - 100% - REDESIGNED WITH ARDUINO UNO PROTOTYPE SHIELD
```

Hardware:
```
RT-Threaad x Renesas RA6M3 HMI-Board
BME280 - Barometric Presure, Humidity & Temperature
SI1145 - UV/IR Light Intnsity Sensor
MPU6050 -  3-Axis Gyroscope Accelerometer
GY-271 -  3-Axis Magnetic Compass
VL53L0X - IR Laser Time-of-Flight Distance Sensor
GT-U7 Serial GPS Module
MQ-X Hydrogen and VOC Gas Sensor
MQ-7 Carbon Monoxide Gas Detector 
3.7v-4.2v > 5v3A Power Converter
Sparkfun MAX17043 Lipo Fuel Gauge
Lipo or Li-ion battery, I used 1200mah from Hobbyking
```

Except for the GPS and MQ Gas Sensors, all of the above sensors operate over I2C, so only 4 pins for each one!

All share the same V, GND, I2C Data & Clock Pins aswell, so a custom PCB makes things alot easier.

This can be done simply on some protoboard, I used an Arduino Uno compatible Protoboard Shield - pictures of this can be found in the __Expansion Board Images__ folder


Software:
```
RT-Thread Studio - for programing the HMI-Board
Squareline Studio - for designing the GUI
Powerpoint - for creating the GUI elements
```

I have created a YouTube tutorial series for how to use the RA6M3 HMI-Board here: [RA6M3 HMI-Board Tutorial Series](https://www.youtube.com/playlist?list=PLK-SamanCEIuBjHlD-6LJ5eWIb0PcgStS)
Detailed Instructions to follow..

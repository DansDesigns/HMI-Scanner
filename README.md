# HMI-Scanner
A multi sensor environment scanner based on the RT-thread x Renesas RA6M3 HMI-Board

Current Progress:
```
GUI - 85%
Code - 75%
3d printed case - WIP
Custom PCB for sensors - 95% - REDESIGNED WITH ARDUINO UNO PROTOTYPE SHIELD
```

Hardware:
```
RT-Threaad x Renesas RA6M3 HMI-Board
BME280 - Barometric Presure, Humidity & Temperature
SI1145 - UV/IR Light Intnsity Sensor
MPU6050 -  3-Axis Gyroscope Accelerometer
GY-271 -  3-Axis Magnetic Compass
VL53L0X - IR Laser Time-of-Flight Distance Sensor
3.7v-4.2v > 5v3A Power Converter
Lipo or Li-ion battery, I used 2000mah
```

The above sensors operate over I2C, so only 4 pins for each one!
All share the same I2C Data & Clock Pins aswell, so a custom PCB makes things alot easier.
This can be done simply on some protoboard or you can order one from the files in the __PCB__ folder from your favourite PCB manufacturer!


Software:
```
RT-Thread Studio - for programing the HMI-Board
Squareline Studio - for designing the GUI
Powerpoint - for creating the GUI elements
EasyEDA - for PCB design
```


Detailed Instructions to follow..

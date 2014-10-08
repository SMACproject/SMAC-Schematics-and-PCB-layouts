# SMAC Schematics and PCB Layouts

## Introduction
This folder includes schematics and PCB layouts for all of SMAC modules.

Design Files can be opened with EAGLE 7.1 free available from http://www.cadsoftusa.com/download-eagle/?language=en

## List of Modules

Module Name | Type | Function | IC  | Diameter [mm] | Ion [mA] | Ioff [mA]
:---------: | :--: | :------: | :-: | :-----------: | :------: | :------:
Master | Master | CPU and wireless communication | CC2530  | 9.8  | 34 | 0.5
3DA | Digital Sensing | 3D Accelerometer | LIS331DLH  | 9 | 0.25 | 0.01
3DG | Digital Sensing | 3D Gyroscope | L3GD20 | 9 | 6.1 | 0.005
3DM | Digital Sensing | 3D Magnetometer | LIS3MDL | 9 | 0.27 | 0.001
3DAG | Digital Sensing | 3D Accel./Gyro. | LIS330DLC | 9.8 | 6.11 | 0.005
3DAM | Digital Sensing | 3D Accel./Magnet. | LSM303D | 9.8 | 0.3 | 0.001
3DAMG | Digital Sensing | 3D Accel./Magnet./Gyro. | LSM9DS0 | 9.8 | 6.15 | 0.005
PT | Digital Sensing | Pressure/Temperature | MPL115A1 | 9.8 | 0.005 | 0.001
8ADC | Analog Sensing | 8 Channels ADC | AD7689 | 9.8 | 03.78 | 0.005
2AFADC | Analog Sensing | 2 Channels Front End & ADC | AD623 & ADS8320  | 9.8 | 2.57 | 0.001
BSDCC | Actuation | Brushed DC Controller | A3901 | 9.5 | - | 0.005
BSLDCC | Actuation | Brushless DC Controller | BH67172NUX | 9.8 | - | 0.009
VI | Vision/Illumination | Vision/Illumination | NUD533 | 9.8 | 150 (Max) | -
PMM | Power Management | Power/Battery Monitoring | TPS33 | 9.8 | 500 (Max) | -
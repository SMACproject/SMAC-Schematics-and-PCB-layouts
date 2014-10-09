# SMAC Schematics and PCB Layouts

## Introduction
This repository contains schematics and board layouts for all of SMAC modules and development platforms.

Design files can be opened with CadSoft EAGLE PCB Design Software, freely available for Windows, Linux and OSX platform from http://www.cadsoftusa.com/download-eagle/?language=en

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
BSDCC | Actuation | Brushed DC Motor Controller | A3901 | 9.5 | - | 0.005
BSLDCC | Actuation | Brushless DC Motor Controller | BH67172NUX | 9.8 | - | 0.009
VI | Vision/Illumination | Vision/Illumination | NUD533 | 9.8 | 150 (Max) | -
PMM | Power Management | Power/Battery Monitor | TPS33 | 9.8 | 500 (Max) | -

## List of Development Kits

Devkit name | Features | Dimension [mm]
:---------: | :------: | :------------:
CC2530EV | CC2530F256, Debugger connector, 2x 8p interface headers, 1x power headers, 1x reset button | 40 x 40
SMAC-2530 | CC2530F256, FT230x USB to serial converter, CC Debugger connector, 2x 10p interface headers, 3x power headers, 1x LCD3310 interface, 4x LEDs, 1x push button, 1x reset button | 62.5 x 57.5
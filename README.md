# Esp_fly
Custom BLDC ESC and an ESP-based flight controller 

Custom Drone Electronics (ESC + ESP Flight Controller)

A fully custom-built drone electronics stack including:
 ESP-based Flight Controller
 30A BLDC Electronic Speed Controller (ESC)


## Overview
This project focuses on building a complete custom drone control system  instead of using off-the-shelf components.

It includes:
ESC design for BLDC motors  
Flight controller using ESP microcontroller  
Schematic + PCB design  
Component selection and optimization  



## Learning & Inspiration
Before building, I explored:
BLDC motor control and ESC architecture  
Flight controller design basics  
Sensor interfacing and control systems  
Open-source projects  

## References
Electronoobs ESC  
BlueESC (SimonK firmware)  
Various open-source drone FC designs  



## Features
Flight Controller
ESP-based microcontroller  
Multiple motor outputs (quad configuration)  
Designed for sensor integration (MPU6050)  
Custom PCB layout  

## ESC
Designed for ~30A current  
3-phase BLDC motor control  
MOSFET-based power stage  
Compact 2-layer PCB  


##PCB Design

 ### Flight Controller

![FC1](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/fc1.png)


![FC2](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/fc2.png)

### ESC
![ESC1](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/esc1.png)


![ESC2](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/esc2.png)

## BOM

| # | Designator | Component            | Quantity | Value / Specs              | Package     | Notes                     |
|---|------------|----------------------|----------|----------------------------|-------------|---------------------------|
| 1 | U1         | ESP32 Module         | 1        | ESP32-WROOM / XIAO ESP32   | Module      | Main controller           |
| 2 | U2         | OLED Display         | 1        | 0.96" I2C (SSD1306)        | Module      | Display output            |
| 3 | U3         | IP5306               | 1        | Power Management IC        | SOP-8       | Battery + boost control   |
| 4 | SW1–SW3    | Push Buttons         | 3        | Momentary tactile          | THT/SMD     | User input                |
| 5 | B1         | Li-ion Battery       | 1        | 3.7V (18650 / LiPo)        | —           | Power source              |
| 6 | R1–R3      | Resistors            | 3        | 10kΩ                       | 0603/0805   | Pull-down (optional)      |
| 7 | C1–C?      | Capacitors           | X        | 0.1µF / 10µF               | 0603/0805   | Decoupling                |
| 8 | J1         | Battery Connector    | 1        | JST-PH 2-pin               | THT         | Battery input             |
| 9 | J2         | USB Connector        | 1        | Micro USB / Type-C         | SMD         | Charging input            |
|10 | —          | Jumper Wires         | —        | —                          | —           | Prototyping               |

## Acknowledgements

- Open-source ESC community  
- Electronoobs  
- Blue Robotics  



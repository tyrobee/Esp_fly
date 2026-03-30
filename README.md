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

| # | Component                     | Qty | Specifications / Part Suggestion        | Purpose                          |
|---|------------------------------|-----|----------------------------------------|----------------------------------|
| 1 | ESP32 Dev Board              | 1   | ESP32 (DevKit / XIAO ESP32)            | Main microcontroller             |
| 2 | OLED Display (0.96" I2C)     | 1   | SSD1306 / SH1106, 128x64               | Display output                   |
| 3 | Push Buttons                 | 3   | Momentary tactile switches             | User input                       |
| 4 | IP5306 Power Module          | 1   | 5V Boost + Charging module             | Power management                 |
| 5 | Li-ion Battery (1S)          | 1   | 3.7V (18650 / LiPo cell)               | Power source                     |
| 6 | Battery Connector            | 1   | JST-PH 2-pin                           | Battery connection               |
| 7 | Jumper Wires                 | 1   | Male-Female / Male-Male                | Connections                      |
| 8 | Resistors (optional)         | 3   | 10kΩ                                   | Pull-down for buttons            |
| 9 | Capacitors                   | 2–4 | 0.1µF + 10µF                           | Power stabilization              |
|10 | PCB / Perfboard              | 1   | Custom PCB or prototyping board        | Mounting components              |
|11 | USB Cable                    | 1   | Type-C / Micro USB                     | Charging + programming           |
## Acknowledgements

- Open-source ESC community  
- Electronoobs  
- Blue Robotics  



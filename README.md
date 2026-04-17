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


## PCB Design

 ### Flight Controller

![FC1](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/fc1.png)


![FC2](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/fc2.png)

### ESC
![ESC1](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/esc1.png)


![ESC2](https://raw.githubusercontent.com/tyrobee/Esp_fly/main/photos/esc2.png)

## Frame
![Wiring Diagram](Cad/Pic_1.png)

## Schematics
![Wiring Diagram 1](photos/c4.png)

## 🧾 Bill of Materials (ESP Drone)

| Name                         | Purpose                                      | Qty | Cost (USD) | Link |
|------------------------------|----------------------------------------------|-----|-----------|------|
| Shipping                     | Shipping                                    | 1   | 10.00     | —    |
| AKKFX Mini VTX 5.8G         | Video transmitter                            | 1   | 21.00     | [Link](#) |
| FlySky FS-iA6B Receiver      | Receiver                                     | 1   | 17.00     | [Link](#) |
| ESP PCB and Pads            | Speed controller                             | 1   | 3.81      | [Link](#) |
| FLIGHT CONTROLLER PCB       | Circuit board                                | 1   | 2.00      | [Link](#) |
| 1046 PROPELLERS             | Push air / lift                              | 2   | 1.15      | [Link](#) |
| MOTOR CCW                   | Thrust                                       | 2   | 11.16     | [Link](#) |
| MOTOR CW                    | Thrust                                       | 2   | 11.16     | [Link](#) |
| FS-i6                       | Transmitter                                  | 1   | 45.00     | [Link](#) |
| MPU6050                     | IMU                                          | 1   | 4.15      | [Link](#) |
| XIAO ESP32 S3               | Microcontroller                              | 1   | 8.65      | [Link](#) |
## Acknowledgements

- Open-source ESC community  
- Electronoobs  
- Blue Robotics  



# Seat Temperature Monitoring System

## Seat Temperature Monitoring System : 
The seat temperature monitoring system is used to control the temperature of a vehicle seat.This system grants a Microcontroller(Atmega328) based Seat measurement system to perceive and confirm the presence/absence of person on the seat. In this system the sensor will sense is the driver has been seated or not and if the driver seated then the temperature need to be set consequently. 

When driver of the car gets settled in a car, the button sensor gets trigger after that heater empowered. The temperature sensor keeps monitoring the temperature and sends analog value of temperature to the microcontroller. The microcontroller alters analog to digital values using ADC and show the numerical value of temperature.


Based on the controller it will set the temperature and it is capable of upholding of heat in the vehicles seats. And whatever the warmness is generated that fact it will be showing on displays.

# Features :

- It perceive whether the person is seated or not.

- It is compitable.

- The numerical value of temperature is envisaged using Pulse Width Modulation(PWM).

- The consistent temperature values displayed.

# SWOT Analysis
<img width="641" alt="image" src="https://user-images.githubusercontent.com/102716839/164390126-2d65c492-f85e-442b-8455-ec110a5389f3.png">

# 4'W and 1'H
- WHY - Well-being for user.

- WHAT - Seat Monitoring System based on Temperature.

- WHEN - Winter seasons and according to user.
 
- WHERE - Used in Transportation,Automobiles.

- HOW - Operates by Temperature Sensor and Microcontroller.

# Requirements

# High Level Requirements
| High Level Requirements  | Description |
| ------------- | ------------- |
| HLR1  | Microcontroller |
| HLR2  | Temperature Sensor |
| HLR3  | Heat Generation |
| HLR4  | Display |
| HLR5  | Software used |

# Low Level Requirements
| Low Level Requirements	  | Description |
| ------------- | ------------- |
| HLR1_LLR1 | ATmega328  |
| HLR2_LLR1 | ADC  |
| HLR2_LLR2 | ADC with PWM-fast  |
| HLR3_LLR1 | Thermoelectric module  |
| HLR4_LLR1 | CRO and LED  |
| HLR5_LLR1 | Code Blocks with AVR GCC compiler  |
| HLR5_LLR2 | SimulIDE  |

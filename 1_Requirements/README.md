# Requirements

## 1. Requirements
### High Level Requirements
| High Level Requirements  | Description |
| ------------- | ------------- |
| HLR1  | Microcontroller - STM32F4 board |
| HLR2  | Software for simulation |
| HLR3  | LED |
| HLR4  | Push button |

### Low Level Requirements
| Low Level Requirements	  | Description |
| ------------- | ------------- |
| HLR1_LLR1 | STM32F4 discovery  |
| HLR2_LLR2 | avr gcc |
| HLR2_LLR3 | xPack - Qemu, xPack - Windows Build Tool, Pack - OpenOCD |
| HLR2_LLR3 | STM32 Cube IDE |
| HLR3_LLR4 | I/O PD12, PD13, PD14, PD15 on STM32F407VGT6 |
| HLR4_LLR5 | Pull-down resistor/ Pull-up resistor  |
| HLR4_LLR6 | PA0 digital pin  |

## 2. What, Why, When, Who ( 4W )
### 4W
#### What 
A wiper speed control system for an wiper controls the operational speed of a wiper in accordance with rain conditions. The control system includes a push button and LED's to control the flickering speed (wiper speed). 
#### Why
To reduce driving distractions and allow drivers to focus on main task of driving. The distraction eliminated with the development of this system is the manual adjustment of wipers when driving in precipitation. 
#### When
Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen. The system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems.
#### Who
For all LMV and HMV needs this system. The wiper serves to clean the windshield of the car at the front and rear, although not all cars have wipers on the rear side. Wiper works by removing oil, dust, rainwater, and dirt that get stuck to the windshield.


 :+1: **Pros :**  Simple, easy to maintain and manage. 
 
 :-1: **Cons :**  It is not automated using any rain sensors
 
### 3. SWOT Analysis
![swot](https://user-images.githubusercontent.com/102242702/168428822-44d80f91-777b-4b09-b9f0-71f560eb0188.PNG)
  
### 4. Implementation Block Diagram 
![control_system](https://user-images.githubusercontent.com/102242702/168428845-1e38d012-7239-4e50-8d5f-b968a1df46a2.PNG)


### The working of motor is visualised via LED's in STM32F4 Discovey Board

## Tools : MS Word, MS Excel and Snipping tool


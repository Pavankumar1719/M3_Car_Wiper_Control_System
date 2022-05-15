# Car Wiper Control System
## Abstract

Car Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on back mirror. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. Not only wiping raindrop it is also used to wipe the dust on the glass while water is stored in car using that water glass can wiped. 

In this proect we will build manually controlled wiper control system. We built a wiper control system using STM32F4 Discovery board. Here we use builtin button and LEDs to operate or visualize the project.We will control onboard four LEDs of STM32F4 discovery board with a push button. 

## Block Diagram

![control_system](https://user-images.githubusercontent.com/102242702/168417729-f629bafa-d956-438c-b1d7-0b6923a3f8e2.PNG)

## Requirements
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
| HLR2_LLR2 | avr gcc/gnu |
| HLR2_LLR3 | xPack - Qemu, xPack - Windows Build Tool, Pack - OpenOCD |
| HLR2_LLR3 | STM32 Cube IDE |
| HLR3_LLR4 | I/O PD12, PD13, PD14, PD15 on STM32F407VGT6 |
| HLR4_LLR5 | Pull-down resistor/ Pull-up resistor  |
| HLR4_LLR6 | PA0 digital pin  |

### The working of motor is visualized in terms of LED action in STM32F4 - Discovery

## Components, Packages and Software required
-   [STM32F4 - Discovery](https://pdf1.alldatasheet.com/datasheet-pdf/view/435284/STMICROELECTRONICS/STM32F4DISCOVERY.html) - Allow users to develop audio applications easily. It includes an ST-LINK/V2-A embedded debug tool, one ST-MEMS digital accelerometer, one digital microphone, one audio DAC with integrated class D speaker driver, LEDs, push-buttons, and a USB OTG Micro-AB connector.Specialized add-on boards can be connected by means of the extension header connectors.
-   [STM32 Cube IDE](https://www.st.com/en/development-tools/stm32cubeide.html) -  STM32CubeIDE is an all-in-one multi-OS development tool, which is part of the STM32Cube software ecosystem. STM32CubeIde Board PhotoSTM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors. 
-   [VS Code](https://code.visualstudio.com/) - Visual Studio Code is a code editor redefined and optimized for building and debugging modern web and cloud applications
-   [LED]() - A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it
-   [Button]() - A push-button (also spelled pushbutton) or simply button is a simple switch mechanism to control some aspect of a machine or a process
-   [Eclipse Embedded CDT](https://projects.eclipse.org/projects/iot.embed-cdt) - It is a plug-ins allow to create, build, debug and in general to manage Arm & RISC-V projects (executables and static/shared libraries, in both 32 and 64-bit versions) with the Eclipse IDE.
-   [xPack Qemu](https://xpack.github.io/qemu-arm/#benefits) - xPack QEMU Arm is a fork of the public open-source QEMU project, customised for more support of Cortex-M cores, and a better integration with the GNU Arm QEMU Debugging plug-in.
-   [xPack OpenOCD](https://xpack.github.io/openocd/#:~:text=The%20xPack%20OpenOCD%20is%20a,code%20available%20from%20the%20repository.) - It is a cross-platform binary distribution of OpenOCD, the Open On-Chip Debugger, an open source project hosted on  SourceForge.
-   [xPack Windoes Build Tool](https://xpack.github.io/windows-build-tools/) -  It is a Windows specific package, customised for the requirements of the Eclipse CDT managed build projects. It includes a recent version of GNU make and a recent version of BusyBox, which provides a convenient implementation for sh/rm/echo.

## Features
-   __Feature-1(System ON):__ The wiper control system becomes active on ___Hold of Button___ or 2 seconds and ___Red LED___ will ___ON___ indicating system is ON.
-   __feature-2(3-Control Levels):__ The system has 3 power levels (i.e, speed of motor in real world), we use (1, 4, 8)Hz as freuency levels used to visualize via LED.
    * When the system ___key press-1___(i.e, the push button is pressed once) the Blue, Green and Orange LED's come ON one at a time with the set frequency of 1Hz
    * When the system ___key press-2___(i.e, the push button is pressed twice) the Blue, Green and Orange LED's come ON one at a time with the set frequency of 4Hz
    * When the system ___key press-3___(i.e, the push button is pressed thrice) the Blue, Green and Orange LED's come ON one at a time with the set frequency of 8Hz
-   __Feature-3(Control Off):__ On key ___press-4___ the system is ON(LED-RED-ON), on press again the system goes back to ___step-2___
-   __Feature-4(System OFF):__ The wiper control system becomes inactive on ___Hold of Button___ or 2 seconds and Red LED will OFF indicating system is OFF.

### The working of motor is visualized in terms of LED action in STM32F4 - Discovery

## User behavior diagram
![Behaviour Flow](https://user-images.githubusercontent.com/102242702/168428584-a11f7646-1f82-4c04-9b46-8ac38a2def7c.PNG)

## Flow chart

![Flow Chart](https://user-images.githubusercontent.com/102242702/168417774-f882de73-14de-4c8a-8a9e-853a201430c5.png)


## What, Why, When, Who ( 4W )
### 4W
#### What 
A wiper speed control system are the operational speed of a wiper in accordance with rain conditions. The control system includes a push button and LED's to control the flickering speed (wiper speed). 
#### Why
To reduce driving distractions and allow drivers to focus on main task of driving. The distraction eliminated with the development of this system is the manual adjustment of wipers when driving in precipitation. 
#### When
Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen. The system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems.
#### Who
For all LMV and HMV needs this system. The wiper serves to clean the windshield of the car at the front and rear, although not all cars have wipers on the rear side. 


 **Pros :**  Simple, easy to maintain and manage. 
 
 **Cons :**  It is not automated using any rain sensors
 
### SWOT Analysis
![swot](https://user-images.githubusercontent.com/102242702/168428822-44d80f91-777b-4b09-b9f0-71f560eb0188.PNG)

## How the project works
1.  __Ignition Key Position at ACC:__ The Red LED is ON, if the user button is pressed and held for 2 secs
2.  __Wiper ON:__ On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz
3.  __Wiper OFF:__ The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2
4.  __Ignition Key Position at Lock:__ The Red LED is OFF, if the user button is pressed and held for 2 secs


# Results

|Key Press - 1 (Wiper power Lvl-1)|Key Press - 2 (Wiper power Lvl-2)|Key Press - 3 (Wiper power Lvl-3)|
|:--:|:--:|:--:|
| ![Key Press - 1](https://user-images.githubusercontent.com/102242702/168414064-1af31028-342e-4f3e-a754-2bf0bc005abe.gif)  | ![Key Press - 2](https://user-images.githubusercontent.com/102242702/168414162-cab0228e-49cf-4fe9-94c9-221a714964fa.gif)  |  ![Key Press - 3](https://user-images.githubusercontent.com/102242702/168414183-5be8a852-5448-423c-8987-b6551201608e.gif) |

|Key Press and Hold - __ON/OFF__|Key Press - 4 (Wiper off)|Key Press - 5(repeat from Wiper power level-1)|
|:--:|:--:|:--:|
| ![Press_hold_on](https://user-images.githubusercontent.com/102242702/168414248-0ffe8362-1028-45b7-84b7-cc6e4aee73fb.gif)  | ![Key Press - 4](https://user-images.githubusercontent.com/102242702/168414262-4e2791a3-5fc4-4559-a6cd-e38d58ad214e.gif)  | ![Key Press - 5](https://user-images.githubusercontent.com/102242702/168414281-bfe9a227-3964-4d1b-a01a-282523b569cd.gif) |


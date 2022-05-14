# Car Wiper Contol System
Car Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on back mirror. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. Not only wiping raindrop it is also used to wipe the dust on the glass while water is stored in car using that water glass can wiped.

In this proect we will build manually controlled wiper control system. We built a wiper control system using STM32F4 Discovery board. Here we use builtin button and LEDs to operate or visualize the project.We will control onboard four LEDs of STM32F4 discovery board with a push button.

![block diaram]![control_system](https://user-images.githubusercontent.com/102242702/168429618-b5eff371-0eba-4c88-8d18-7f1ef6a6bd07.PNG)


### The working of motor is visualised via LEDs in STM32F4 - Discovery board

## Folder Structure
| Folder | Discription |
| :---: | :---: | 
| 0_Absract | Brief info aout project
| 1_Requirements	| Documents detailing requirements and research
| 2_Design	| Documents specifying design details
| 3_Implementation |	All code, neccesary files and documentation
| 4_TestPlanAndOutput | All the test files and 
| 6_ImagesAndvedios | Contains output and media files

## In Action
|ON|OFF|
|:--:|:--:|
|![ON](https://github.com/Lokesh12121/M3_Wiper_Conytol_System_stm32f4/blob/main/6_ImagesAndVideos/ON_state.gif)|![OFF](https://github.com/Lokesh12121/M3_Wiper_Conytol_System_stm32f4/blob/main/6_ImagesAndVideos/OFF_state.gif)|

## Working Scenario
|Key Press - 1 (Wiper power Lvl-1)|Key Press - 2 (Wiper power Lvl-2)|Key Press - 3 (Wiper power Lvl-3)|
|:--:|:--:|:--:|
|![Key Press - 1](https://user-images.githubusercontent.com/102242702/168429757-4e2183f4-f1e6-4d36-9d34-30a270af1836.gif)|![Key Press - 2](https://user-images.githubusercontent.com/102242702/168429794-b16cbcf2-8f16-4752-9f27-331b0e7af90e.gif)|![Key Press - 3](https://user-images.githubusercontent.com/102242702/168429826-c2a0c931-2765-426a-82fb-70ada7ce75a1.gif)|

|Key Press and Hold - __ON/OFF__|Key Press - 4 (Wiper off)|Key Press - 5(repeat from Wiper power level-1)|
|:--:|:--:|:--:|
| ![Press_hold_on](https://user-images.githubusercontent.com/102242702/168429849-0cdf9633-e2af-46c4-b018-9e3051f63c03.gif) | ![Key Press - 4](https://user-images.githubusercontent.com/102242702/168429868-211a6106-6c18-4086-a7d6-7720d1d0332a.gif) | ![Key Press - 5](https://user-images.githubusercontent.com/102242702/168429881-56e7f003-91eb-4701-9285-8be1f514473b.gif) |

## CI and Code Quality

| Complile | Cppcheck | Codacy | Build CI | Git_Inspector
|:--:|:--:|:--:|:--:|:--:|
| [![Compile-Linux] | [![Cppcheck] | [![Codacy Badge] | [![Build_CI - Linux]| [![Bulid CI - windows]  | [![Git Inspector]|


# High Level Test Plan
| Test ID  | Description | Exp I/P | Exp O/P | Actual O/P | Type of Test |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- 
| H_01  | System Testing  | LED - ON when all the doors and windows closed  | Pass  | Pass  | Requirement Based  |
| H_02  | System Testing  | Convert the analog signal from the temperature sensor to the digital value | Pass  | Pass  | Boundary Based  |
| H_03  | System Testing  | Generate the PWM signal according to the converted digital value  | Pass  | Pass  | Scenario Based  |
| H_04  | System Testing  | Send the temperature value to the serial monitor using UART protocol  | Pass  | Pass  | Boundary Based  |

# Low Level Test Plan
| Test ID  | Description | I/P | O/P | Status |
| ------------- | ------------- | ------------- | ------------- | -------------
| H_01  | If server room closed   | Push button=1  | Push button=1  | Pass  |
| H_02  | If server room opened  | Push button=0  | Push button=0  | Pass  |
| H_03  | Temperature Request  | Temperature=0  | Heater=Off  | Pass  |
| H_04  | Temperature Request  | Temperature=20  | Room Temperature=20 degree generation | Pass  |
| H_05  | Temperature Request  | Temperature=25  | Room Temperature=25 degree generation  | Pass  |
| H_06  | Temperature Request  | Temperature=29  | Room Temperature=29 degree generation  | Pass  |
| H_07  | Temperature Request  | Temperature=33  | Room Temperature=33 degree generation  | Pass  |
| H_08  | LED ON | Buttons=1 && Room Temperature=1 | LED=1  | Pass  |
| H_08  | LED OFF | Buttons=0 && Room Temperature=0  | LED=0  | Pass  |
| H_08  | Display | Temperature :- 20 deg Cel  | Temperature :- 20 deg Cel  | Pass  |

# Results

## Working Scenario
|Key Press - 1 (Wiper power Lvl-1)|Key Press - 2 (Wiper power Lvl-2)|Key Press - 3 (Wiper power Lvl-3)|
|:--:|:--:|:--:|
| ![Key Press - 1](https://user-images.githubusercontent.com/102242702/168414064-1af31028-342e-4f3e-a754-2bf0bc005abe.gif)  | ![Key Press - 2](https://user-images.githubusercontent.com/102242702/168414162-cab0228e-49cf-4fe9-94c9-221a714964fa.gif)  |  ![Key Press - 3](https://user-images.githubusercontent.com/102242702/168414183-5be8a852-5448-423c-8987-b6551201608e.gif) |

|Key Press and Hold - __ON/OFF__|Key Press - 4 (Wiper off)|Key Press - 5(repeat from Wiper power level-1)|
|:--:|:--:|:--:|
| ![Press_hold_on](https://user-images.githubusercontent.com/102242702/168414248-0ffe8362-1028-45b7-84b7-cc6e4aee73fb.gif)  | ![Key Press - 4](https://user-images.githubusercontent.com/102242702/168414262-4e2791a3-5fc4-4559-a6cd-e38d58ad214e.gif)  | ![Key Press - 5](https://user-images.githubusercontent.com/102242702/168414281-bfe9a227-3964-4d1b-a01a-282523b569cd.gif) |

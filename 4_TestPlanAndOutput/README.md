### High Level Test Plan
| Test ID  | Description | Exp I/P | Exp O/P | Actual O/P | Type of Test |
| ------------- | ------------- | ------------------------------- | ------- | --------  | ----------- |
| HL_1  | System testing | Press Push button once LED ON | Pass | Pass | Speed test for wiper level-1 |
| HL_2  | System testing | Press Push button 2nd time LED ON | Pass | Pass | Speed test for wiper level-2 |
| HL_3  | System testing | Press Push button 3rd time LED ON | Pass | Pass | Speed test for wiper level-3 |
| HL_4  | System testing | Press and Hold push button | Pass | Pass | To check whether it is on/off |

### Low Level Test Plan
| Test ID | Description | I/P | O/P | Status  |
| ------------- | ------------- | ------- | ------- | ------- |
| LL_1 | Press push button for 4th time | Pass | Pass | Wiper gets turn off |
| LL_2 | Press push button for 5th time | Pass | Pass | Once again it repeate back to step HL_2 |
| LL_3 | Press and Hold for 2second Push button | Pass | Pass | RED LED gets turn on indicates ignition on | 


# Results

## Working Scenario
|Key Press - 1 (Wiper power Lvl-1)|Key Press - 2 (Wiper power Lvl-2)|Key Press - 3 (Wiper power Lvl-3)|
|:--:|:--:|:--:|
| ![Key Press - 1](https://user-images.githubusercontent.com/102242702/168414064-1af31028-342e-4f3e-a754-2bf0bc005abe.gif)  | ![Key Press - 2](https://user-images.githubusercontent.com/102242702/168414162-cab0228e-49cf-4fe9-94c9-221a714964fa.gif)  |  ![Key Press - 3](https://user-images.githubusercontent.com/102242702/168414183-5be8a852-5448-423c-8987-b6551201608e.gif) |

|Key Press and Hold - __ON/OFF__|Key Press - 4 (Wiper off)|Key Press - 5(repeat from Wiper power level-1)|
|:--:|:--:|:--:|
| ![Press_hold_on](https://user-images.githubusercontent.com/102242702/168414248-0ffe8362-1028-45b7-84b7-cc6e4aee73fb.gif)  | ![Key Press - 4](https://user-images.githubusercontent.com/102242702/168414262-4e2791a3-5fc4-4559-a6cd-e38d58ad214e.gif)  | ![Key Press - 5](https://user-images.githubusercontent.com/102242702/168414281-bfe9a227-3964-4d1b-a01a-282523b569cd.gif) |

# 1. HIGH LEVEL TEST PLAN

| Test ID | Description | Input | Expected output | Actual Output | Test Type |
| --- | --- | --- | --- | --- | --- |
| 01 | Ignition ON | User Button Press and hold for 2sec | Red LED ON | Red LED ON | Scenario indicating System ON |
| 02 | Viper ON | User Button Press Button 1st tme  | Blue, Green, Orange LEDs Flicker with 1Hz | Blue, Green, Orange LEDs Flicker with 1Hz  | Wiper power level-1 |
| 03 | Viper ON | User Button Press Button 2nd time | Blue, Green, Orange LEDs Flicker with 4Hz | Blue, Green, Orange LEDs Flicker with 4Hz  | Wiper power level-2 |
| 04 | Viper ON | User Button Press Button 3rd time | Blue, Green, Orange LEDs Flicker with 8Hz | Blue, Green, Orange LEDs Flicker with 8Hz  | Wiper power level-3 |
| 05 | Ignition OFF | User Button Press and hold for 2sec |  Red LED OFF | Red LED OFF | Scenario indicating System OFF |

# 2. LOW LEVEL TEST PLAN
### For LEDs
| Test ID | Description | Input | Expected output | Actual Output | Test Type |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for Ignition ON | Button Press and hold for 2sec | Pass | Pass | Test and view in hardware |
| 02 | Check for Wiper power level-1 | Button Press 1st time | Pass | Pass | Test and view in hardware |
| 03 | Check for Wiper power level-2 | Button Press 2nd time | Pass | Pass | Test and view in hardware |
| 04 | Check for Wiper power level-3 | Button Press 3rd time | Pass | Pass | Test and view in hardware |
| 05 | Check for Ignition OFF | Button Press and hold for 2sec | Pass | Pass | Test and view in hardware |

# Results

|Key Press - 1 (Wiper power Lvl-1)|Key Press - 2 (Wiper power Lvl-2)|Key Press - 3 (Wiper power Lvl-3)|
|:--:|:--:|:--:|
| ![Key Press - 1](https://user-images.githubusercontent.com/102242702/168414064-1af31028-342e-4f3e-a754-2bf0bc005abe.gif)  | ![Key Press - 2](https://user-images.githubusercontent.com/102242702/168414162-cab0228e-49cf-4fe9-94c9-221a714964fa.gif)  |  ![Key Press - 3](https://user-images.githubusercontent.com/102242702/168414183-5be8a852-5448-423c-8987-b6551201608e.gif) |

|Key Press and Hold - __ON/OFF__|Key Press - 4 (Wiper off)|Key Press - 5(repeat from Wiper power level-1)|
|:--:|:--:|:--:|
| ![Press_hold_on](https://user-images.githubusercontent.com/102242702/168414248-0ffe8362-1028-45b7-84b7-cc6e4aee73fb.gif)  | ![Key Press - 4](https://user-images.githubusercontent.com/102242702/168414262-4e2791a3-5fc4-4559-a6cd-e38d58ad214e.gif)  | ![Key Press - 5](https://user-images.githubusercontent.com/102242702/168414281-bfe9a227-3964-4d1b-a01a-282523b569cd.gif) |

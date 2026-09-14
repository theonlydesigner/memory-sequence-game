# Memory Sequence Game

A custom Simon Says-style memory game hardware project featuring an onboard Arduino Nano, multi-colored LED array, tactile pushbuttons and dual haptic/buzzer feedback [because pressing buttons without audio-visual chaos is boring].

![3D View Preview](https://github.com/user-attachments/assets/dba25dcc-ff4f-4421-8e8b-7270147b23f5)

## Overview

This project is an all-in-one memory game board built around the Arduino Nano. It combines 4 distinct color LEDs (Red, Green, Blue, Yellow), 4 matching tactile buttons, audio tone generation and vibration feedback into a clean, standalone PCB footprint. Designed for simple assembly, standalone power handling and easy reprogramming.

## Features

* **Dynamic Sequence Generation:** Randomized color patterns generated each level with an integrated countdown timer to force quick decisions.
* **Audio-Haptic Feedback:** Each button press triggers a dedicated pitch note alongside vibration motor/buzzer feedback.
* **Dedicated Power Delivery:** Onboard DC barrel jack and voltage regulator setup to run off external DC power without frying components.
* **Hardware Controls:** Dual slide switches dedicated to master power toggle and volume/feedback control.
* **Repurposable Microcontroller Hub:** Built around female pin headers for the Arduino Nano, allowing the core board to be reused for other dev projects.

## Gallery

### Schematic & Layout

| Schematic Design | PCB 2D Layout Top | PCB 2D Layout Bottom |
| :---: | :---: | :---: |
| ![Schematic](https://github.com/user-attachments/assets/87543ece-d745-4e6a-9178-385615a96e9b) | ![PCB Top](https://github.com/user-attachments/assets/cc6943fd-274e-4d6d-bc7b-f6b4f3e19633) | ![PCB Bottom](https://github.com/user-attachments/assets/1f0c578b-615c-48f1-b54a-45440cc144c7) |

### 3D Model Renders

| Perspective View | Top Isometric |
| :---: | :---: |
| ![3D View 1](https://github.com/user-attachments/assets/dba25dcc-ff4f-4421-8e8b-7270147b23f5) | ![3D View 2](https://github.com/user-attachments/assets/81867eaa-a067-4879-b80a-6c65b5857a79) |

| Side Profile | Rear Power & Port Angle |
| :---: | :---: |
| ![3D View 3](https://github.com/user-attachments/assets/ce6683f0-4ca5-43e7-af80-b5f534f15883) | ![3D View 4](https://github.com/user-attachments/assets/0cd59666-eed0-4e7c-bdf4-72c2a9de195c) |

## Bill of Materials (BOM)

| Item | Quantity | Description / Package |
| :--- | :---: | :--- |
| **Arduino Nano** | 1 | Microcontroller (with female pin headers) |
| **Colored LEDs** | 4 | 1x Red, 1x Green, 1x Blue, 1x Yellow |
| **Current Limiting Resistors** | 4 | 220Ω through-hole / axial |
| **Tactile Pushbuttons** | 4 | Standard 4-pin momentary switches |
| **Feedback Motor / Buzzer** | 1 | Vibration motor or piezo buzzer |
| **DC Barrel Jack** | 1 | Standard DC power input jack |
| **Slide Switches** | 2 | SPDT switches (Power & Volume controls) |
| **Voltage Regulator** | 1 | Onboard linear voltage regulator |
| **JST Connector** | 1 | Auxiliary power connector |

## How to Assemble

1. **Low-Profile Components:** Solder the 4x 220Ω current-limiting resistors first.
2. **Semiconductors & Switches:** Mount the 4 LEDs (pay attention to anode/cathode orientation), voltage regulator and slide switches.
3. **Interactive Hardware:** Solder the 4 tactile pushbuttons, DC barrel jack, vibration motor/buzzer and JST connector.
4. **Header Sockets:** Solder the female pin headers for the Arduino Nano socket.
5. **Mount & Flash:** Insert the Arduino Nano into the headers, upload the game code via USB-C/Mini-USB and flip the power switch.

## Credits

* **Designer:** Pratham Rupera (`theonlydesigner`)
* **Platform:** Built for Hack Club

# Water Level Controller Using 8051

This project is an automated **Water Level Controller** using the **8051 microcontroller**, designed to monitor and manage water levels in a tank efficiently. It prevents overflow, conserves water, and automates water pumping based on tank levels. This mini-project was developed as part of the course curriculum at **MITWPU**.

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Software Requirements](#software-requirements)
- [Circuit Design](#circuit-design)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The **Water Level Controller Using 8051** is designed to automatically control the water level in a tank. It uses water level sensors to detect the water levels and controls a motor to start or stop the water flow based on predefined thresholds, conserving water and preventing overflow.

## Project Overview
The system uses an **8051 microcontroller** to process input from water level sensors and controls the motor. When the water level drops below a certain point, the motor is turned on to fill the tank. When the tank reaches a full level, the motor is turned off.

## Features
- **Real-Time Water Level Monitoring**: Continuously monitors the water level using sensors.
- **Automatic Motor Control**: Turns the motor on/off based on detected water level.
- **Efficient Water Usage**: Reduces water waste by automating the filling process.
- **User Notifications**: Optional LED indicators or display for visual status updates.

## Hardware Components
- 8051 Microcontroller
- Water level sensors
- Relay module (to control the motor)
- Motor/pump
- Power supply
- Connecting wires and PCB/breadboard

## Software Requirements
- **Keil µVision** (for programming the 8051 microcontroller)
- **Proteus** or **Multisim** (optional, for circuit simulation)
- **EdSim51** (for 8051 microcontroller simulation)
- **8051 Assembler** or **C Compiler** (for coding)

## Circuit Design
The circuit comprises the following parts:
1. **8051 Microcontroller**: Processes the water level inputs and controls the relay.
2. **Water Level Sensors**: Senses the levels at different points (e.g., empty, half, full).
3. **Relay Module**: Controls the motor based on signals from the microcontroller.
4. **Motor**: Turns on/off to fill the tank.

Please refer to the `Circuit_Diagram.png` file in this repository for the complete schematic.

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/username/Water-Level-Controller-8051.git
   ```
2. Open the code files in **Keil µVision** or your preferred 8051 IDE.
3. If you want to simulate the project, use **EdSim51** to run and test the 8051 code with virtual hardware.
4. Compile the code and upload it to the 8051 microcontroller.
5. Assemble the circuit as per the circuit diagram provided.
6. Connect the microcontroller to the circuit and power on.

## Usage
1. Power on the system.
2. The water level sensor will detect the water level in the tank.
3. The microcontroller will automatically turn the motor on or off based on the tank’s water level.
4. Monitor the LED/display (if included) to see the current status of the tank.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

# Voice Controlled Pick and Place Robot

## Overview

The **Voice Controlled Pick and Place Robot** is an embedded system project that uses **Arduino Uno** to control a robotic arm via **voice commands** sent through a Bluetooth module. This project is designed to help individuals with disabilities, automate industrial tasks, and operate in hazardous environments.

## Features

- **Voice-Controlled Operations**: Move the robot and control the robotic arm using voice commands.
- **Bluetooth Communication**: HC-05 module enables wireless control via an Android app.
- **Pick and Place Mechanism**: Uses servo motors for gripping and lifting objects.
- **LCD Display**: Provides feedback on received commands and system status.
- **Motorized Movement**: The robot moves forward, backward, left, and right using DC motors.

## Components Used

| Component                        | Quantity |
| -------------------------------- | -------- |
| Arduino Uno                      | 1        |
| HC-05 Bluetooth Module           | 1        |
| L293D Motor Driver IC            | 1        |
| DC Motors                        | 2        |
| Servo Motors                     | 3        |
| LCD Display (16x2)               | 1        |
| Lithium-Ion Battery              | 2        |
| Robot Chassis                    | 1        |
| Miscellaneous (Wires, PCB, etc.) | Various  |

## Circuit Connections

- **Arduino Uno**: Controls the entire system.
- **HC-05 Bluetooth Module**: Connected to TX/RX of Arduino for receiving commands.
- **L293D Motor Driver**: Controls DC motors for movement.
- **Servo Motors**: Operate the robotic arm for pick and place actions.
- **LCD Display**: Provides system status and feedback.
- **Power Supply**: Li-Ion battery provides power to the entire system.

## Installation & Setup

1. Clone this repository:
   ```sh
   git clone https://github.com/HARSITHRAM/voice-pick-place-robot.git
   ```
2. Install the **Arduino IDE** and necessary libraries:
   - Servo.h
   - LiquidCrystal.h
3. Upload the Arduino code to the **Arduino Uno** board.
4. Pair your **HC-05 Bluetooth module** with an Android device.
5. Use a voice control app to send commands.

## Commands List

| Command | Function       |
| ------- | -------------- |
| 1       | Pick Object    |
| 2       | Place Object   |
| 3       | Move Arm Up    |
| 4       | Move Arm Down  |
| 5       | Rotate Arm     |
| 6       | Straighten Arm |
| 7       | Move Forward   |
| 8       | Move Backward  |
| A       | Turn Right     |
| B       | Turn Left      |
| 0       | Stop Robot     |

## Applications

- **Assistive Technology**: Helps disabled individuals operate objects remotely.
- **Industrial Automation**: Can be used in factories for material handling.
- **Hazardous Environments**: Works in dangerous areas where human intervention is risky.

## Future Enhancements

- **Integration with AI**: Implementing an AI-based voice recognition system.
- **Camera Integration**: Adding a camera for object detection and automation.
- **Wi-Fi Control**: Using ESP8266/ESP32 for cloud-based control.

## Contributing

Feel free to fork this repository and submit pull requests for improvements. Contributions are always welcome!

## License

This project is **open-source** under the MIT License.

## Contact

For any questions or collaboration, feel free to reach out:

- **GitHub**: [@HARSITHRAM](https://github.com/HARSITHRAM)
- **Email**: [harsithram](mailto\:harsithram08@gmail.com)


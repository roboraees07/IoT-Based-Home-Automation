# IoT-Based-Home-Automation
This project demonstrates a simple yet effective home automation system using NodeMCU, relay modules, and the Blynk mobile application. The system allows users to control household appliances such as lights, fans, and other devices through a mobile app, providing convenience and energy efficiency.

# Home Automation System using NodeMCU and Blynk

![Home Automation Banner](banner.jfif)

## Overview

This project implements a home automation system that allows users to control various household appliances using NodeMCU and the Blynk mobile application. The system is designed to be cost-effective, scalable, and easy to use, providing remote control and monitoring capabilities for connected devices.

## Table of Contents

- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Circuit Diagram](#circuit-diagram)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **Remote Control**: Turn devices on or off from anywhere using the Blynk app.
- **Real-time Feedback**: Receive immediate updates on the status of your devices.
- **Scalability**: Add additional devices and relays as needed.
- **Low Cost**: Built using affordable components like NodeMCU and relay modules.
- **User-Friendly**: Easy to set up and operate with the Blynk app.

## Hardware Requirements

- NodeMCU (ESP8266) Development Board
- Relay Modules (as per the number of devices to control)
- Jumper Wires
- Breadboard (optional)
- Household Appliances (e.g., lights, fans)

## Software Requirements

- Arduino IDE
- Blynk App (available on iOS and Android)
- Blynk Library for Arduino

## Circuit Diagram

![Circuit Diagram](images/circuit_diagram.png)

## Installation

1. **Set up the Blynk App:**
   - Download the Blynk app from the [App Store](https://apps.apple.com/us/app/blynk-iot/id808760481) or [Google Play Store](https://play.google.com/store/apps/details?id=cc.blynk).
   - Create a new project and note the Auth Token provided by the app.
   - Add buttons in the app to control the appliances.

2. **Configure the NodeMCU:**
   - Connect the relay module to the NodeMCU as per the circuit diagram.
   - Open the Arduino IDE and install the Blynk library using the Library Manager.
   - Use the provided sketch in this repository (`HomeAutomation.ino`) and update it with your Wi-Fi credentials and Blynk Auth Token.

3. **Upload the Sketch:**
   - Connect the NodeMCU to your computer via USB.
   - Select the appropriate board and port in the Arduino IDE.
   - Upload the sketch to the NodeMCU.

## Usage

- Open the Blynk app and connect to the project.
- Use the app's buttons to control the connected appliances.
- Monitor the status of each appliance in real-time through the app.

## Troubleshooting

- **Connection Issues**: Ensure the NodeMCU is connected to the correct Wi-Fi network and that the Blynk app has the right Auth Token.
- **Relay Malfunction**: Check the wiring and ensure the relay is receiving power.
- **App Not Responding**: Restart the Blynk app or reset the NodeMCU to re-establish the connection.

## Contributing

We welcome contributions to enhance the functionality of this project. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy building your home automation system! For any questions or support, please open an issue in this repository.

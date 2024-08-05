
# Android RAT (Remote Access Trojan)

## Overview

This Android RAT (Remote Access Trojan) is a proof-of-concept application designed to demonstrate how a Remote Access Trojan can be implemented on Android devices using Java. The RAT provides functionality for remote control and monitoring of an Android device.

**Disclaimer:** This project is for educational purposes only. The use of RATs in unauthorized or malicious ways is illegal and unethical. Ensure that you have proper authorization before testing or deploying this software.

## Features

- **Remote Control:** Allows the attacker to remotely control the infected device.
- **Command Execution:** Executes arbitrary commands on the device.
- **File Access:** Access and manage files on the infected device.
- **Screen Capture:** Captures screenshots of the device's screen.
- **Location Tracking:** Retrieves GPS location of the device.
- **Contact List Access:** Access and manage the device's contact list.

## Prerequisites

- **Java Development Kit (JDK):** Ensure that you have JDK 8 or higher installed.
- **Android SDK:** You need the Android Software Development Kit for building the application.
- **Android Studio:** It is recommended to use Android Studio for development and debugging.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/mithunmadhukuttan/android-rat.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd android-rat
   ```

3. **Open the Project in Android Studio:**
   - Launch Android Studio and select "Open an existing Android Studio project."
   - Navigate to the cloned directory and open it.

4. **Build the Project:**
   - Click on "Build" > "Make Project" in Android Studio.

5. **Run the Application:**
   - Connect an Android device or use an emulator.
   - Click on "Run" > "Run 'app'" in Android Studio.

## Usage

1. **Install the APK:**
   - Build the APK file using Android Studio and install it on the target device.

2. **Control the Device:**
   - Launch the application on the target device and follow the provided instructions to establish a connection with the control server.

3. **Interact with the Device:**
   - Use the control panel to issue commands and monitor the device remotely.

## Important Notes

- **Ethical Use:** This RAT should only be used in controlled, legal environments with explicit permission from the device owner.
- **Security Risks:** Running this RAT on a device could expose sensitive information and should only be done for educational or testing purposes within secure environments.


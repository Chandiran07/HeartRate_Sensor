# HeartRate_Sensor
# Pulse Oximeter with MAX30100 and OLED Display

# Overview
This project utilizes the MAX30100 pulse oximeter sensor to measure heart rate (BPM) and oxygen saturation (SpO2). The data is displayed on an OLED screen using the OakOLED library.

# Table of Contents
Pulse Oximeter with MAX30100 and OLED Display
Overview
Table of Contents
Hardware Requirements
Software Requirements
Installation
Usage
Customization
Contributing
License
Acknowledgments

# Hardware Requirements
1.MAX30100 Pulse Oximeter Sensor
2.OLED Display
3.Arduino or compatible microcontroller
4.Connecting wires
5.Power source
# Software Requirements
1.Arduino IDE
2.OakOLED Library
3.MAX30100 Library
# Installation
Clone the repository:

bash
Copy code
git clone https://github.com/chandiran07/pulse-oximeter.git
cd pulse-oximeter
Open the Arduino IDE and install the required libraries: OakOLED and MAX30100.

Connect the MAX30100 and OLED display to your Arduino following the provided circuit diagram.

Upload the pulse_oximeter.ino sketch to your Arduino.

# Usage
Connect the pulse oximeter hardware.
Open the Arduino IDE and upload the sketch to your Arduino.
Open the serial monitor to view heart rate (BPM) and oxygen saturation (SpO2) data.
Observe the OLED display for real-time BPM and SpO2 readings.
# Customization
.Modify the bitmap array in the sketch to change the displayed icon on beat detection.
.Adjust the reporting period and OLED display positions as needed.
# Contributing
If you'd like to contribute to this project, please follow these steps:

1.Fork the repository.
2.Create a new branch for your feature or bug fix.
3.Make your changes and submit a pull request.
# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
1.Special thanks to Adafruit for the OakOLED library.
2.Inspired by the need for a simple, DIY pulse oximeter.

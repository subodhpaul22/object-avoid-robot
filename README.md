# object-avoid-robot
This is an Autonomous Object Avoiding Robot built using an Arduino/ESP32 and an ultrasonic sensor. The robot detects obstacles in its path and intelligently navigates around them using a motor driver and DC motors.
Introduction

This is an Autonomous Object Avoiding Robot built using an Arduino/ESP32 and an ultrasonic sensor. The robot detects obstacles in its path and intelligently navigates around them using a motor driver and DC motors.

Features

Uses an Ultrasonic Sensor (HC-SR04) for object detection

Autonomous navigation without external control

Controlled by Arduino/ESP32

Driven by DC motors & L298N Motor Driver

Battery-powered for portability

Components Required

Component

Quantity

Arduino Uno/Nano or ESP32

1

Ultrasonic Sensor (HC-SR04)

1

DC Motors

2

L298N Motor Driver

1

Robot Wheels

2

Chassis

1

Battery (9V/12V or Li-ion)

1

Jumper Wires

As needed

Switch

1

Circuit Diagram

[Upload an image of the circuit diagram here]

Wiring Instructions

HC-SR04 Ultrasonic Sensor:

VCC → 5V (Arduino) / 3.3V (ESP32)

Trig → D9 (Arduino) / GPIO12 (ESP32)

Echo → D10 (Arduino) / GPIO14 (ESP32)

GND → GND

L298N Motor Driver:

IN1 → D4 (Arduino) / GPIO4 (ESP32)

IN2 → D5 (Arduino) / GPIO5 (ESP32)

IN3 → D6 (Arduino) / GPIO18 (ESP32)

IN4 → D7 (Arduino) / GPIO19 (ESP32)

12V → Battery Positive

GND → Battery Negative & Arduino GND
How to Use

Assemble the hardware as per the circuit diagram.

Upload the provided code to your Arduino/ESP32.

Power on the robot using a battery.

The robot will start moving forward and avoid obstacles automatically.

Future Improvements

Adding IR Sensors for better obstacle detection.

Implementing AI-based Path Planning.

Integrating Bluetooth/WiFi Control for manual override.

License

This project is open-source under the MIT License. Feel free to modify and share!


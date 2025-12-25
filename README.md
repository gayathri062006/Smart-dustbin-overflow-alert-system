# Smart Dustbin Overflow Alert IoT System
Goal: Detect the dustbin’s fill level using sensors and give an early alert to prevent overflow and poor waste management.
## Features
The ultrasonic sensor measures the height/level of the garbage inside the bin.
When the measured level crosses a set threshold, a buzzer and LED alert are activated.
The system is developed and tested using Arduino and Wokwi simulation.
In the future, GSM or WiFi can be added to send notifications to the cloud or as messages.
## Hardware & Tools
Arduino Uno or Arduino Nano
Ultrasonic sensor (HC‑SR04)
Buzzer, LEDs, resistors, jumper wires
9V battery or USB power supply
Wokwi online simulator
## How It Works
The ultrasonic sensor is fixed at the top of the dustbin and measures the distance to the garbage surface.
If the distance becomes less than a preset limit (meaning the bin is almost full), the system detects it as “FULL” and turns on the buzzer and LED.
The current dustbin level is shown on the Serial Monitor or an LCD display, and the threshold values can be adjusted in the code.
## Simulation
Wokwi project link:https://wokwi.com/projects/451109316772246529
## Code
Main code file: smart_dustbin_overflow.ino

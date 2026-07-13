# Transistor Tester

## Overview
The Transistor Tester is an Arduino Nano-based embedded system project developed to identify Bipolar Junction Transistors (BJTs). It detects whether the transistor is NPN or PNP and identifies the Base, Collector, and Emitter terminals. The detected results are displayed on a 16×2 LCD, making transistor testing simple, fast, and accurate.

## Features
- Detects NPN and PNP transistors
- Identifies Base, Collector, and Emitter pins
- Displays the transistor type and pin configuration on a 16×2 LCD
- Simple push-button operation
- Low-cost and portable design

## Components Used
- Arduino Nano
- 16×2 LCD Display
- Push Button
- 470Ω Resistors
- Breadboard
- Jumper Wires
- NPN and PNP Transistors

## Circuit Connections
- LCD Display
  - VCC → 5V
  - GND → GND
  - SDA → A4
  - SCL → A5
- Push Button
  - One terminal → A3
  - Other terminal → GND
- Test Pins
  - D2 → A0
  - D3 → A1
  - D4 → A2

## Working Principle
When the push button is pressed, the Arduino Nano applies different voltage combinations to the transistor terminals using digital pins D2, D3, and D4. The analog pins A0, A1, and A2 measure the corresponding voltages. Based on these readings, the system determines whether the transistor is NPN or PNP and identifies its Base, Collector, and Emitter terminals. The result is displayed on the LCD.

## Project Files
- TransistorTester.ino
- Transistor Tester FINAL Project.pdf
- Circuit Diagram
- Block Diagram
- Hardware Images

## Applications
- Electronics Laboratory
- Educational Projects
- Transistor Testing
- Embedded Systems Learning
- Electronics Troubleshooting

## Future Improvements
- Support MOSFET and JFET testing
- Measure transistor gain (hFE)
- Use an OLED display
- Improve testing accuracy

## Conclusion
This project demonstrates a simple and effective Arduino Nano-based Transistor Tester. It provides a quick and reliable method to identify NPN and PNP transistors and determine their pin configuration, making it useful for students, hobbyists, and electronics enthusiasts.

## Author
Laxmi Shekayi

Electronics and Communication Engineering (ECE)

Smt. Kamala & Sri Venkappa M. Agadi College of Engineering & Technology

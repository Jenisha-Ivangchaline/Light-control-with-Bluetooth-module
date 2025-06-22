# Light-control-with-Bluetooth-module

#  Arduino-Based Light Control Using Bluetooth Module

This project allows you to **control a light wirelessly via Bluetooth** using an Arduino and a Bluetooth module (HC-05/HC-06). It demonstrates the basics of wireless communication between a smartphone and an Arduino microcontroller for simple home automation.

##  Features

- Bluetooth-enabled light ON/OFF control
- Mobile phone as a wireless remote
- Simple and cost-effective design
- Ideal for beginners in IoT and embedded systems
- Expandable for smart home automation

##  Components Used

 Arduino Uno
 HC-05/HC-06 Bluetooth Module 
 Relay Module (5V)      
 LED             
 Smartphone with Bluetooth 
 Jumper Wires           
 Breadboard (optional)  


##  Working Principle

1. The Bluetooth module receives commands from a paired smartphone.
2. Arduino processes the received signal via serial communication.
3. Based on the command (e.g., `ON`/`OFF`), it triggers the relay.
4. The relay acts as a switch to turn the light ON or OFF.

##  Android App Suggestions

You can use any Bluetooth Terminal app like:

- [Serial Bluetooth Terminal (Google Play)](https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal)
- Arduino Bluetooth Controller

Send commands:
- `ON` → Turns the light ON
- `OFF` → Turns the light OFF

## Applications

This project demonstrates basic Bluetooth-based home automation. It can be applied in various real-world scenarios such as:
- Smart Home Lighting: Control room lights wirelessly using a mobile phone.
- Bedroom Automation: Switch off lights from bed without getting up.
- Elderly Assistance: Provide easy light control for people with limited mobility.
- Educational Projects: Ideal for students to learn embedded systems and wireless communication.

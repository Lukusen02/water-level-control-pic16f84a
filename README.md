# Water Level Control System using PIC16F84A

This project implements an automatic water tank level monitoring and control system using the PIC16F84A microcontroller. The system detects the level of water inside a container using conductive electrodes placed at different heights. Depending on the detected level, the microcontroller activates LED indicators and controls a water pump to automatically refill the tank when necessary.

The purpose of this project is to demonstrate the use of microcontrollers in monitoring and control applications, combining digital electronics, sensor interfaces, and actuator control.

## System Description

The system uses one reference electrode placed at the bottom of the tank and five additional electrodes positioned at different heights representing different water levels.

As the water level rises, the liquid closes the electrical circuit between the reference electrode and the corresponding level electrode. These signals are detected by the microcontroller through transistor-based switching circuits.

The microcontroller processes the inputs and performs the following actions:

- Indicates the current water level using LED indicators.
- Activates a water pump when the water level falls below the minimum level.
- Deactivates the pump automatically when the tank reaches the maximum level.

This control logic ensures that the tank is automatically filled when needed while preventing overflow.

## Main Features

- Water level detection using conductive sensors
- LED indicators for visual level monitoring
- Automatic pump activation and deactivation
- Microcontroller-based control system
- Assembly language programming
- Simulation and hardware implementation

## Hardware Components

The main components used in this project include:

- PIC16F84A microcontroller
- PNP transistors for level detection
- NPN transistor for pump control
- LEDs for level indication
- Resistors
- Breadboard
- Jumper wires used as electrodes
- Small DC water pump (9V)
- 5V power supply for the microcontroller

## Development Process

The project was developed in several stages. First, the control algorithm was implemented and tested through simulation using Proteus. During this stage, DIP switches were used to simulate the level sensors and LEDs were used to represent the outputs.

After validating the logic of the system, the program was loaded into the microcontroller and implemented on a breadboard. The DIP switches were later replaced with conductive electrodes placed in a water container to detect real water levels.

## Repository Structure

code/ → Assembly source code for the PIC16F84A  
simulation/ → Proteus simulation files  
hardware/ → Circuit diagrams and prototype images  
docs/ → Project documentation

## Academic Information

This project was developed for the course:

Digital Systems with Microcontrollers and Laboratory  
Universidad Pontificia Bolivariana – Montería

Professor:  
Marcos R. Gómez Sierra

Authors:

Juan Pablo González  
Samuel Martínez

Year: 2026

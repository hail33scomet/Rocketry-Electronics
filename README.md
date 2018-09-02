# Rocketry-Electronics
This repository includes the PCB design work that I developed for a suborbital rocketry team. 
The main boards inside of the avionics bay and nosecone were developed as a stackable modular quarter circle design with a radius of 6 cm.
Other boards were developed to be placed inside the payload bay.
All boards were designed with Altium and use an 11.1V Li-ion battery pack

1. Analog Parachute Circuitry/ Regulatory circuitry for flight computer - Circuitry for the 2 parachutes used to ignite an electric match, as well as for continuity checking requirements, reverse polarity, voltage regulation for flight computer
2. On board flight computer - SWD STM32 MCU, sd card, barometer, accelrometer used for apogee detection
3. Airbrakes System - ATMega 2560 MCU, motor drivers for stepper motors
4. Telemetry System 5V/3.3V 1.5A buck converter
5. Electrical Switch -isolated from individual payload power sources
6. Cosmic Ray PCB

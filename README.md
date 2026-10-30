# Hermes Vision

Smart glasses designed to detect driver drowsiness using computer vision and multiple sensors.

## About the Project

Hermes Vision monitors signs of driver fatigue using eye movement, blinking, head movement and other sensor readings. The aim is to detect drowsiness early and alert the driver.

## Project Overview

<!-- Upload: A clear picture of the complete Hermes Vision glasses prototype -->
![Hermes Vision Prototype](images/hermes-vision-prototype.jpg)

## How It Works

- The camera tracks the driver's eyes and blinking.
- The system monitors head movement to detect possible microsleep.
- The MAX30102 measures heart rate and blood oxygen levels.
- Sensor readings are combined to assess possible drowsiness.
- An alert is triggered when signs of fatigue are detected.



## Hardware

- Raspberry Pi Zero 2 W
- Raspberry Pi Camera V2 NoIR
- MAX30102 heart-rate and SpO₂ sensor
- MPU6050 accelerometer and gyroscope
- 940nm infrared LEDs
- Custom-designed PCB
- Battery and power management components

<!-- Upload: A picture of the electronics and components -->
![Hardware Components](images/hardware-components.jpg)

## PCB Design

The project uses a custom PCB to connect the sensors and other electronic components.


## Software

The software processes camera and sensor data to monitor the driver's condition and identify possible signs of drowsiness.


## Repository Contents

- `website.html` – Project website
- `PCB/` – PCB design files
- `images/` – Project photographs and diagrams

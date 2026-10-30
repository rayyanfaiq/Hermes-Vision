# Hermes Vision

Smart glasses designed to detect driver drowsiness using computer vision and multiple sensors.

## About the Project

Hermes Vision monitors signs of driver fatigue using eye movement, blinking, head movement and other sensor readings. The aim is to detect drowsiness early and alert the driver.

## Project Overview


<img width="1600" height="739" alt="image" src="https://github.com/user-attachments/assets/c00b6be6-1e6f-486c-848c-069c7289ef93" />


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


## PCB Design

The project uses a custom PCB to connect the sensors and other electronic components.


## Software

The software processes camera and sensor data to monitor the driver's condition and identify possible signs of drowsiness.

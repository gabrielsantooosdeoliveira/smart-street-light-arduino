# Smart Street Light System with Arduino

An automated street lighting prototype developed using Arduino and an HC-SR04 ultrasonic sensor.

## Project Overview

This project simulates an intelligent street lighting system that automatically activates street lights when a vehicle or object approaches.

The HC-SR04 ultrasonic sensor measures the distance to nearby objects. When an object is detected within 27 cm, two LEDs turn on for 10 seconds, simulating street lights illuminating the road.

The main goal is to demonstrate how automation can help optimize energy consumption in public lighting systems.

## Project Preview

![Smart Street Light Prototype](images/Captura_de_tela_2026-11-19_102356.png‎)

## Components

- Arduino board
- HC-SR04 ultrasonic sensor
- 2 LEDs
- Breadboard
- Jumper wires
- Model street setup

## How It Works

1. The ultrasonic sensor measures the distance to nearby objects.
2. The Arduino processes the distance measurement.
3. If an object is detected within 27 cm, both LEDs turn on.
4. The LEDs remain on for 10 seconds and then turn off.
5. Distance measurements are displayed through the Serial Monitor.

## Pin Configuration

| Component | Arduino Pin |
|---|---|
| HC-SR04 Trig | 11 |
| HC-SR04 Echo | 10 |
| LED 1 | 13 |
| LED 2 | 12 |

## Technologies

- Arduino
- C/C++
- HC-SR04 ultrasonic sensor
- Basic automation

## Academic Project

Developed as part of a technical learning project at Fundação Bradesco.

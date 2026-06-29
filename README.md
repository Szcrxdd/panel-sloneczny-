# Solar Tracker with Arduino

A simple one-axis solar tracking system built with Arduino UNO. The project uses two LDR light sensors to detect the direction of the strongest light source and automatically adjusts a servo motor to orient a small solar panel.

## Features
- One-axis solar tracking
- Two LDR sensors for light detection
- Servo motor control
- Automatic panel positioning
- Stable tracking using threshold and sensor filtering

## Components
- Arduino UNO
- SG90 Servo Motor
- 2× KY-018 LDR Light Sensor Modules
- Mini Solar Panel
- Breadboard & Jumper Wires

## Technologies
- Arduino (C/C++)
- Arduino IDE

## How it works
The Arduino continuously reads values from two LDR sensors. If one sensor detects significantly more light than the other, the servo rotates the panel toward the brighter side. A threshold prevents unnecessary oscillation when both sensors receive similar light levels.

## Author
Created as a mechatronics school project.

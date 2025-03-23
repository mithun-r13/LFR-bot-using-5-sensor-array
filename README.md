LFR Bot Using 5 Sensor Array, Motor Driver (L298D), and Arduino Uno

Overview

This repository contains the code and instructions to build a Line Follower Robot (LFR) using a 5-sensor array, an L298D motor driver, and an Arduino Uno. The robot detects a black line on a white surface and follows it autonomously with improved accuracy and smoother turns.

Components Required

Arduino Uno (Main controller)

L298D Motor Driver (Controls motors)

5 IR Sensor Array (Detects the line)

2 DC Motors (For movement)

Chassis (Base structure)

Wheels (For mobility)

Power Supply (9V or 12V battery)

Jumper Wires (For wiring connections)

Circuit Diagram



Circuit Connections

IR Sensor Array to Arduino:

Leftmost Sensor → A0

Left Sensor → A1

Middle Sensor → A2

Right Sensor → A3

Rightmost Sensor → A4

Motor Driver (L298D) to Arduino:

Motor 1 (Left Motor)

IN1 → Pin 7

IN2 → Pin 8

ENA → 11 

Motor 2 (Right Motor)

IN3 → Pin 10

IN4 → Pin 9

ENB → 6


Power Connections:

L298D VCC → 9V Battery

L298D GND → Arduino GND

L298D 5V Output → Arduino 5V

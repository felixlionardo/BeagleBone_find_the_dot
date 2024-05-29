# Find the Dot Game

## Overview

This project is for the CMPT 433 course, Assignment 4: PRU + Linux - Find the Dot, instructed by Dr. Brian Fraser. The assignment involves creating a game where the user angles the board up/down and left/right to find a hidden dot. The user is guided by the NeoPixel light strip, uses the joystick to shoot the dot, and hears sounds from the buzzer.

## Game Demo
https://www.youtube.com/watch?v=-4HGtYqb4II

## Features

- **NeoPixel LED Strip Control**: PRU controls the NeoPixel LED strip, displaying different colors and patterns to guide the user.
- **Accelerometer Integration**: Determines the board's tilt to guide the user in finding the hidden dot.
- **Joystick Control**: Allows the user to "fire" at the dot and exit the application.
- **14-Segment Display**: Shows the number of successful hits.
- **PWM Buzzer**: Plays different sounds for hits and misses.
- **Startup/Shutdown**: Proper setup and shutdown of all components.

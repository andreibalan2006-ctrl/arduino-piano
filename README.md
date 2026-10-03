# Arduino 6-Key Mini Piano

## Overview
This project is a simple 6-key electronic piano built with an Arduino Uno. It uses push buttons to play different musical notes through a piezo buzzer[cite: 1].

## Hardware Components
- Arduino Uno board
- Breadboard
- 6 x Push Buttons
- 1 x Piezo Buzzer
- Jumper wires

## Wiring Instructions
- **Power:** Connect the `5V` and `GND` pins from the Arduino to the breadboard's power rails[cite: 1].
- **Buzzer:** Connect one pin of the buzzer to Arduino Digital Pin `8` and the other pin to the `GND` rail[cite: 1].
- **Buttons:** Connect one side of each of the 6 push buttons to the `GND` rail[cite: 1]. Connect the other side of each button to Arduino Digital Pins `2`, `3`, `4`, `5`, `6`, and `7`[cite: 1].

## Usage
1. Build the circuit as described above.
2. Upload your piano sketch (`.ino` file) to the Arduino board.
3. Press the buttons to play different notes!

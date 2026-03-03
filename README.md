##  Project Overview

This project implements a hardware-based version of the Google Dino Game.  
The dinosaur jumps to avoid randomly generated obstacles. The score increases for every obstacle successfully crossed. The game ends when a collision occurs.

---

##  Features

- Real-time gameplay on 16x2 LCD Display
- Random obstacle generation
- Push button controlled jump
- Buzzer sound effects
- Score tracking
- Game over detection
- Hardware-software integration
- PCB-based assembly for better usability

---

##  Components Used

| Component        |
|------------------|
| Arduino Uno      | 
| Push Button      | 
| Buzzer           |
| Jumper Wires     | 
| PCB              |
   |

---

##  Hardware Connections

- LCD connected using I2C module (SDA, SCL)
- Push Button connected to digital input pin
- Buzzer connected to digital output pin
- All components powered via Arduino 5V and GND

---

##  Game Flow

1. Press push button to start the game.
2. Dinosaur and obstacles begin moving.
3. Press button to jump and avoid collision.
4. If obstacle is crossed:
   - Score increases.
   - Buzzer sounds.
5. If collision occurs:
   - Buzzer signals game over.
   - Final score displayed on LCD.

---



##  Learning Outcomes

- Practical understanding of Arduino
- Working with I2C LCD module
- Embedded C programming
- Hardware-software integration
- Circuit design & PCB implementation
- Team collaboration

---





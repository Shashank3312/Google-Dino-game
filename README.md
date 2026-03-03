# 🦖 Google Dinosaur Game (Arduino Version)

An embedded systems project that recreates the classic Google Chrome Dinosaur Game using **Arduino Uno**, an **I2C LCD Display**, **Push Button**, and **Buzzer**.

---

## 📌 Project Overview

This project implements a hardware-based version of the Google Dino Game.  
The dinosaur jumps to avoid randomly generated obstacles. The score increases for every obstacle successfully crossed. The game ends when a collision occurs.

---

## 🎯 Features

- Real-time gameplay on 16x2 LCD Display
- Random obstacle generation
- Push button controlled jump
- Buzzer sound effects
- Score tracking
- Game over detection
- Hardware-software integration
- PCB-based assembly for better usability

---

## 🛠️ Components Used

| Component        | Cost (INR) |
|------------------|------------|
| Arduino Uno      | 600        |
| Push Button      | 10         |
| Buzzer           | 99         |
| Jumper Wires     | 100        |
| PCB              | 11         |
| **Total Cost**   | **820**    |

---

## 🔌 Hardware Connections

- LCD connected using I2C module (SDA, SCL)
- Push Button connected to digital input pin
- Buzzer connected to digital output pin
- All components powered via Arduino 5V and GND

---

## 🔄 Game Flow

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

## 📷 Demo Video

[Click Here to Watch Demo](https://photos.app.goo.gl/aKwjLF4nArZE4kzR9)

---

## 💡 Learning Outcomes

- Practical understanding of Arduino
- Working with I2C LCD module
- Embedded C programming
- Hardware-software integration
- Circuit design & PCB implementation
- Team collaboration

---

## 👥 Team Members

- Ganipisetty Nischal
- Batta Venkata Shashank

Team ID: 39  

---

## 📚 References

- Arduino Official Documentation
- LiquidCrystal I2C Library
- Online I2C and LCD tutorials
- OpenAI (for debugging support)

---

## 🚀 Future Improvements

- Add high score memory (EEPROM)
- Increase game speed gradually
- Add multiple difficulty levels
- Improve graphics using custom characters

---

⭐ If you like this project, feel free to star the repository!

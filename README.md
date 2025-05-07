# 💡 LED Blinking using 8051 Microcontroller

This is a simple embedded C project that demonstrates how to blink an LED using the **8051 microcontroller (AT89C51)**. The program toggles an LED connected to pin **P2.0** at regular intervals, creating a continuous blinking effect.

---

## ✅ Features

- LED toggles ON and OFF with a delay
- Uses software delay loop
- Designed to run at 12 MHz crystal frequency

---

## 🔧 Hardware Requirements

- AT89C51 / 8051 Microcontroller
- LED
- Resistor (220Ω – 330Ω) for current limiting
- Power supply (5V)
- Breadboard and jumper wires

---

## 🧠 How it Works

1. The LED is connected to **P2.0** pin of the microcontroller.
2. A delay function is created using nested loops to generate approximately 1 ms delay per iteration.
3. The LED is turned ON and OFF alternately with a 50 ms delay between each transition.

---

## 📁 File Structure

- `led_blinking.c` – Source code file
- `README.md` – Project documentation

---

## 🛠 Tools Used

- **Keil µVision** – For writing and compiling embedded C code
- **Proteus** – For circuit simulation
- **8051 Development Board** – For real hardware testing

---

## 💡 Circuit Diagram

![Led_blink_8051_output](https://github.com/user-attachments/assets/2978c4f2-e35e-47a3-94ae-fea3c9969766)

---

## 🔄 Output

The LED connected to P2.0 will blink with a 50 ms ON and 50 ms OFF time continuously.

## 👨‍💻 Developed By

Vamsi T
Graduate Engineer (ECE)  
vamsithummaluri@gmail.com


This project is intended for educational purposes and is open for learning and non-commercial use.

---

© 2025 Vamsi T – All Rights Reserved

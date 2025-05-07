# 🔐 Password-Based Door Lock System using 8051 Microcontroller

This project demonstrates a password-protected door lock system built using an **8051 microcontroller** and a **4x3 keypad**, with a **16x2 LCD display** for user interaction. It validates a 6-digit password and controls a motor and buzzer based on input correctness.

---

## ✅ Features

- 6-digit password authentication (`630199`)
- Keypad input with LCD feedback
- LCD messages for guidance and status
- Motor control for door simulation
- Buzzer alert on incorrect password
- Access granted/denied messages

---

## 🔧 Hardware Requirements

- AT89C51 / 8051 Microcontroller
- 16x2 LCD Display
- 4x3 Matrix Keypad
- DC Motor (to simulate door mechanism)
- Buzzer
- Power Supply (5V)
- Resistors (pull-ups if required)
- Breadboard and connecting wires

---

## 🧠 How it Works

1. System boots up and shows "PASSWORD CHECKING SYSTEM" on the LCD.
2. User is prompted to enter a 6-digit password using the keypad.
3. Each input is masked with an asterisk `*`.
4. If the entered password is correct:
   - Message: `"ACCESS GRANTED"`
   - Motor runs (door opens)
   - Buzzer remains silent
5. If incorrect:
   - Message: `"PASSWORD WRONG"` and `"TRY AGAIN"`
   - Buzzer sounds briefly
   - Password input restarts

---

## 📁 File Structure

- `password_checker_code.txt` – Source code written in Embedded C for the 8051 microcontroller
- `README.md` – Project overview, usage, and hardware description

---

## 🛠 Tools Used

- **Keil µVision** – Writing and compiling embedded C code
- **Proteus** – Circuit design and simulation
- **8051 Development Board** – Real hardware testing

---

## 📷 Output Preview

![Led_blink_8051_output](https://github.com/user-attachments/assets/2978c4f2-e35e-47a3-94ae-fea3c9969766)

---

## 👨‍💻 Developed By

Vamsi T
Graduate Engineer (ECE)  
vamsithummaluri@gmail.com



---

## 🛡 License

This project is intended for educational purposes and is open for learning and non-commercial use.

---

© 2025 Vamsi T – All Rights Reserved

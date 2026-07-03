# 💡 LED Blink using Arduino UNO

## 📌 Project Overview
This project demonstrates the basic operation of digital output pins on the Arduino UNO by blinking an LED at fixed time intervals.

## 🎯 Objective
- Learn the basics of Arduino programming.
- Understand digital output control.
- Generate a blinking pattern using software delays.
- 
## 🛠️ Components Required
| Component | Quantity |
|-----------|----------|
| Arduino UNO | 1 |
| LED | 1 |
| 220Ω Resistor | 1 |
| Breadboard | 1 |
| Jumper Wires | As required |
| USB Cable | 1 |

## 🔌 Circuit Connections

| Arduino Pin | Component |
|--------------|-----------|
| D13 | LED Anode (+) |
| GND | LED Cathode (-) |

> **Note:** If using the onboard LED, no external LED or resistor is required.

## ⚙️ Working Principle

The Arduino continuously sends a HIGH signal to Digital Pin 13, turning the LED ON. After a delay of one second, it sends a LOW signal, turning the LED OFF. This process repeats indefinitely, creating a blinking effect.

## 📂 Project Structure
01_LED_Blink_Arduino
│
├── README.md
├── code
│   └── LED_Blink.ino
│
├── images
│   ├── circuit.jpg
│   ├── setup.jpg
│   └── output.jpg
│
└── datasheet (Optional)
```
## 💻 Source Code

The complete Arduino program is available in:
code/LED_Blink.ino
```

---

## 📷 Circuit Diagram

Add your circuit diagram here.

```
images/circuit.jpg
```

---

## 📸 Hardware Setup

Add your hardware setup image here.

```
images/setup.jpg
```

---

## ▶️ Output

The LED blinks continuously with a delay of one second between ON and OFF states.

Add an output image or GIF.

```
images/output.jpg
```

---

## 🚀 Applications

- Status indication
- Power indication
- Embedded system testing
- Hardware debugging
- Learning digital I/O concepts
- Basic automation projects

---

## 📚 Concepts Learned

- Arduino IDE
- Arduino Sketch Structure
- setup() Function
- loop() Function
- pinMode()
- digitalWrite()
- delay()
- Digital Output Pins

---

## 🧠 Learning Outcome

After completing this project, I learned:

- Basic Arduino programming.
- Configuring GPIO pins as outputs.
- Controlling LEDs using software.
- Understanding the execution flow of setup() and loop().
- Building and uploading sketches to an Arduino UNO.

---

## 🔮 Future Improvements

- Blink multiple LEDs.
- Control blinking using a push button.
- Replace delay() with millis().
- Create different LED patterns.
- Implement PWM-based LED fading.

---

## 📖 References

- Arduino Official Documentation  
  https://docs.arduino.cc/

- Arduino UNO Datasheet  
  https://docs.arduino.cc/hardware/uno-rev3/

---

## 👨‍💻 Author

**Byre Gowda T N**

Electronics and Communication Engineering

Embedded Systems | IoT | Robotics Enthusiast

GitHub: https://github.com/byregowdatn

---

⭐ If you found this repository useful, consider giving it a star.

# 📌 PID-Controlled Ball Balancing System

# 📖 Overview

This system stabilizes a ball on a platform by adjusting its tilt using PID control. It uses an Arduino Uno, ultrasonic sensor, and servo motor for real-time control.

# 🚀 Features

• Real-time feedback control to maintain the ball’s position.

• Uses PID control for dynamic balance adjustments.

• Implements servo motors to tilt the platform dynamically.

• Demonstrates closed-loop control principles.

# 🛠 Hardware Components

• Arduino Uno (Microcontroller)

• Ultrasonic Sensor (Measures ball position)

• Servo Motors (Tilt platform for balance)

• Ball Platform (For balancing the ball)

• Power Supply & Wiring

# 🖥 Software Requirements

• Arduino IDE (For code compilation and upload)

• C++ (Arduino Programming Language)

• PID Library for Arduino

# 🏗 How to Run

1. Clone this repository:
   ```sh
   it clone https://github.com/your-username/ball-balancing-system.git
   cd ball-balancing-system

2. Upload the code to an Arduino board using Arduino IDE:
   ```sh
   arduino-cli compile --fqbn arduino:avr:uno ball_balance.ino
   arduino-cli upload -p /dev/ttyUSB0 --fqbn arduino:avr:uno ball_balance.ino

3. Monitor real-time performance:
   ```sh
   arduino-cli monitor -p /dev/ttyUSB0 -b 115200

# 👨‍💻 Contributing

Feel free to fork and improve each project. Open a pull request with any enhancements.

# 📜 License

Each project is open-source and available under the MIT License.
   












   

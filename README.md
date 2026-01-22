⏳ Smart Digital Hourglass (Bluetooth & MPU6050)
A modern take on the classic hourglass, this project uses an Arduino Nano and an MPU6050 sensor to simulate sand particles on LED matrices. The particles react to gravity in real-time and the timer can be controlled remotely via Bluetooth.

🌟 Features
Real-time Physics Simulation: Sand particles move based on the precise gravity data from the MPU6050 accelerometer.

Bluetooth Time Adjustment: Change the countdown duration (in minutes) wirelessly using an HC-05 module and any Bluetooth terminal app.

Dual Matrix Display: A seamless visualization across two 8x8 LED matrices.

Autonomous Power: Optimized to run on a rechargeable 18650 Li-ion battery pack for portability.

🛠 Hardware Components
Microcontroller: Arduino Nano

Sensor: MPU6050 (6-axis Accelerometer & Gyroscope)

Display: 2x MAX7219 8x8 LED Matrix (Daisy-chained)

Communication: HC-05 Bluetooth Module

Power Source: 18650 Li-ion Battery (3.7V)

Feedback: Piezo Buzzer (for timer alarm)

Component,Arduino Pin,Description
MPU6050 SDA,A4,I2C Data Line
MPU6050 SCL,A5,I2C Clock Line
LED Matrix DIN,D5,Data Input
LED Matrix CLK,D4,Clock Signal
LED Matrix CS,D6,Chip Select
Bluetooth RXD,D3,Arduino TX (SoftwareSerial)
Bluetooth TXD,D2,Arduino RX (SoftwareSerial)
Buzzer,D13,Alarm Output

![IMAGE 2026-01-22 14:28:01](https://github.com/user-attachments/assets/615e71f4-4b59-46d7-a2d6-83b8a360c81b)
![IMAGE 2026-01-22 14:28:22](https://github.com/user-attachments/assets/b32e0ad6-0071-4433-b8b1-a7fe252ac415)





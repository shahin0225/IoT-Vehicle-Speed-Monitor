IoT Vehicle Speed Monitor system
Project Overview

The IoT-Based Vehicle Speed Monitoring System is designed to monitor the speed of a moving vehicle using sensors and a microcontroller. It measures the time taken by a vehicle to travel between two sensors and calculates its speed.

The system helps identify vehicles travelling above the specified speed limit. It displays the measured speed and can alert the user when the vehicle exceeds the speed limit.

🎯 Objectives

- To monitor vehicle speed in real time.
- To calculate vehicle speed using two sensors.
- To detect overspeeding vehicles.
- To improve road safety.
- To provide an alert when the speed limit is exceeded.

🛠️ Components Required

1. Arduino Uno
2. IR Sensor – 2
3. LCD Display (16×2) – Optional
4. Buzzer – Optional
5. Breadboard
6. Jumper Wires
7. USB Cable
8. Power Supply

⚙️ Working Principle

1. Two IR sensors are placed at a fixed distance from each other.
2. When a vehicle passes the first sensor, the Arduino records the starting time.
3. When the vehicle reaches the second sensor, the Arduino records the ending time.
4. The time difference is calculated.
5. The vehicle speed is calculated using the formula:

Speed = Distance / Time

6. If the calculated speed exceeds the set speed limit, an alert is generated.

🧮 Speed Calculation

Formula:

Speed (m/s) = Distance (m) / Time (seconds)

Speed (km/h) = Speed (m/s) × 3.6

Example:

- Distance between sensors = 0.20 metres
- Time taken = 0.5 seconds
- Speed = 0.20 / 0.5 = 0.4 m/s
- Speed = 1.44 km/h

💻 Software Required

- Arduino IDE
- Tinkercad (for simulation)
- Embedded C / Arduino Programming

🔌 Applications

- Smart traffic monitoring
- Highway speed monitoring
- Vehicle speed detection
- Road safety systems
- Educational IoT projects

✅ Advantages

- Simple and low-cost system.
- Real-time speed measurement.
- Easy to implement.
- Helps identify overspeeding.
- Can be upgraded with IoT technology.

🚀 Future Enhancements

- Connect the system to an ESP8266 Wi-Fi module.
- Upload speed data to the ThingSpeak cloud platform.
- Send overspeed alerts to a mobile phone.
- Store vehicle speed records online.
- Add GPS for vehicle location tracking.

📊 Result

The system successfully calculates vehicle speed using two IR sensors and an Arduino. It can identify overspeeding based on the predefined speed limit.

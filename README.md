Real-Time Health Monitoring System (RHMS)
Overview

The Real-Time Health Monitoring System (RHMS) is an IoT-based embedded system built using ESP32. It monitors vital health parameters such as heart rate, body temperature, and motion in real time. The system also detects sudden falls and triggers an alert using a buzzer during abnormal conditions.

Objectives:

Monitor heart rate using MAX30105
Measure body temperature using DS18B20
Detect falls using MPU6050
Trigger emergency alert using buzzer

Hardware Components:

ESP32
MAX30105 Sensor
DS18B20 Temperature Sensor
MPU6050 Accelerometer and Gyroscope
Buzzer

Software Used:

Arduino IDE
Embedded C++
Sensor libraries

Working:

The ESP32 continuously reads sensor data and processes it in real time. If abnormal readings or sudden fall detection occurs, the buzzer is activated. Sensor data is displayed using the Serial Monitor.

Future Improvements:

Cloud integration
Mobile application dashboard
Emergency notification system
Data logging and visualization

Author:
Y Roopa
B.E. Artificial Intelligence and Data Science

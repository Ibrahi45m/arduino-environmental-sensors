# Arduino Environmental Sensors Project

This repository contains a set of Arduino-based environmental sensing experiments developed using different sensors and simple alert mechanisms.

The project focuses on sensor interfacing, analog and digital data acquisition, threshold-based decision making, and real-time monitoring using the Arduino Serial Monitor.

---

## Project Overview

The system includes three main sensing modules:

- DHT11 temperature and humidity sensor
- MQ-2 gas sensor
- Water level sensor

Each sensor was tested separately using an Arduino Uno and implemented on real hardware.

---

## Hardware Used

- Arduino Uno
- DHT11 temperature and humidity sensor
- MQ-2 gas sensor
- Water level sensor
- Buzzer
- LED
- Breadboard
- Jumper wires
- USB cable

---

## Software

- Arduino IDE
- C/C++
- Serial Monitor

---

## 1. MQ-2 Gas Detection

The MQ-2 gas sensor is used to detect changes in gas concentration.

The sensor output is read through an analog input of the Arduino Uno.

A predefined detection threshold is used to determine when the gas concentration becomes significant.

When the measured value exceeds the threshold, the Arduino activates a buzzer as an alert.

### Main Concepts

- Analog sensor reading
- Threshold-based decision logic
- Buzzer control
- Serial communication

### Hardware Prototype

![MQ-2 Sensor Setup](docs/images/mq2_sensor_setup.jpg)

### Code and Testing

![MQ-2 Code](docs/images/mq2_code_serial.jpg)

---

## 2. DHT11 Temperature and Humidity Monitoring

The DHT11 sensor is used to measure ambient temperature and relative humidity.

The Arduino reads the measurements from the sensor and displays them in real time through the Serial Monitor.

### Main Concepts

- Digital sensor communication
- Temperature measurement
- Humidity measurement
- Real-time data monitoring

### Hardware Prototype

![DHT11 Sensor](docs/images/dht11_sensor.jpg)

### Serial Monitor Output

![DHT11 Serial Output](docs/images/dht11_serial_output.jpg)

## 3. Water Level Detection

The water level sensor is connected to an analog input of the Arduino Uno.

The Arduino continuously reads the sensor value and compares it with a predefined threshold.

Depending on the measured value, an LED can be activated to indicate the detected water level condition.

Main Concepts
Analog data acquisition
Threshold comparison
LED control
Sensor calibration
Serial monitoring
Hardware Prototype

Skills Demonstrated

This project demonstrates practical experience in:

Arduino programming in C/C++
Embedded sensor interfacing
Analog and digital data acquisition
Environmental monitoring
Threshold-based decision systems
Serial communication
Hardware prototyping
Breadboard circuit implementation
Basic embedded alert systems
Possible Improvements

The project can be extended by integrating all sensors into a single monitoring platform.

Possible future improvements include:

ESP32 integration
Wi-Fi connectivity
MQTT communication
Cloud data storage
Web or mobile dashboard
Automatic notifications
Data logging
Remote environmental monitoring
Smart agriculture applications

## Author

Ibrahim Ait Massoud

Embedded Systems and Electronics Student
Mohammed V University in Rabat

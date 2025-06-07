# IoT-projects
Embedded cybersecurity projects 

# IoT Projects – Smart Embedded Systems

## Overview

This repository contains various IoT (Internet of Things) projects created for academic, experimental, and practical learning purposes. Each project integrates microcontrollers (such as Arduino or ESP), sensors, and communication modules to build smart, connected systems.

The main focus is on developing functional embedded applications that interact with their environment and transmit or display data in real time.

## Features

- Sensor data acquisition and real-time monitoring
- Use of IoT platforms (e.g., ThingSpeak, Blynk, MQTT)
- Embedded programming with Arduino IDE
- Wireless communication via WiFi and Bluetooth
- Low-power microcontroller-based solutions
- Project scalability and modular code

## Technologies & Tools

- Arduino (UNO, Nano, ESP8266, ESP32)
- C/C++ programming
- IoT platforms: ThingSpeak, Blynk, MQTT brokers
- Sensors: DHT11/DHT22 (temperature/humidity), PIR, LDR, ultrasonic, etc.
- Actuators: LEDs, buzzers, relays
- WiFi & Bluetooth modules

## Example Projects

| Project                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `iot_temperature_logger` | Logs environmental temperature and humidity to ThingSpeak via ESP8266       |
| `smart_motion_alarm`     | PIR-based motion detection system that sends alerts over WiFi               |
| `wifi_led_controller`    | Web-controlled LED system using ESP and onboard server                      |
| `iot_weather_station`    | Multi-sensor weather station with live data display                         |

*Note: Actual folders and file names may differ based on local organization.*

## Setup & Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AlexandruGabrielBrabete/IoT-projects.git
   ```

2. **Open in Arduino IDE**
   - Launch Arduino IDE.
   - Open the `.ino` file corresponding to the project you wish to upload.
   - Select the correct board (e.g., ESP8266 or Arduino UNO) and COM port.

3. **Install Required Libraries**
   Use the Library Manager to install any necessary dependencies (e.g., `DHT sensor library`, `Adafruit Unified Sensor`, `WiFiClient`, etc.).

4. **Upload and Test**
   - Connect your board via USB.
   - Upload the code and monitor results via Serial Monitor or IoT dashboard.

## Folder Structure

```
/IoT-projects
├── iot_temperature_logger/
│   └── temperature_logger.ino
├── smart_motion_alarm/
│   └── motion_alarm.ino
├── wifi_led_controller/
│   └── led_controller.ino
└── ...
```

## Author

**Name:** Alexandru-Gabriel Brabete  
**University:** Technical University of Cluj-Napoca  
**Field:** Electronics, Telecommunications and Information Technology  
**Year:** 2nd year.

## License

This project is provided for academic and educational purposes. Distribution and reuse allowed with proper attribution.

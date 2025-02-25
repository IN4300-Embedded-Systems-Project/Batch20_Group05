
# IoT Smart Farming System 🌱💧

The IoT Smart Farming System automates irrigation using real-time soil moisture data. It employs an ESP32 microcontroller, moisture sensors, an LDR sensor, and an OLED display to monitor conditions and control a water pump. The system integrates with Arduino IoT Cloud, enabling remote monitoring and manual control via a dashboard.


## Features

- Automated Irrigation – Waters plants based on real-time soil moisture levels.
- Sunlight Detection – Uses an LDR sensor to optimize irrigation timing.
- IoT Connectivity – Remote monitoring and control via Arduino IoT Cloud.
- OLED Display – Real-time sensor data visualization.
- Manual & Auto Mode – Allows switching between manual and automatic irrigation.
- Power Efficient – Uses a Type-C power supply for stable operation.



## Components Used

🔧 **Hardware Components**
- ESP32 Microcontroller – Core processing unit, manages sensors, display, and Wi-Fi connectivity.
- Soil Moisture Sensor – Measures soil moisture levels to determine irrigation needs.
- Light Dependent Resistor (LDR) – Detects sunlight to optimize irrigation timing.
- SSD1306 OLED Display – Displays real-time sensor values and system status.
- Water Pump – Supplies water to the crops when moisture levels are low.
- Relay Module – Controls the water pump based on system logic.
- Power Supply (Type-C) – Provides stable power to all components.

🖥️ **Software Components** 
- Arduino IoT Cloud – Enables remote monitoring and control.
- Wi-Fi Connectivity – Connects ESP32 to the internet for IoT functions.
- Arduino Libraries – Includes ArduinoIoTCloud.h, Arduino_ConnectionHandler.h, Wire.h, - Adafruit_GFX.h, and Adafruit_SSD1306.h for handling cloud, display, and sensor functions.
- Sensor Data Processing – Reads and maps soil moisture and light intensity values.
- Relay Control – Automates the irrigation process based on sensor data.
- OLED Display Handling – Visualizes sensor readings and system status.
- Serial Debugging – Logs real-time data for analysis and troubleshooting.
## Circuit Diagram

![App Screenshot](https://res.cloudinary.com/srilankan-cloudname/image/upload/v1740496289/WhatsApp_Image_2025-02-25_at_4.25.59_PM_bzl3yy.jpg)


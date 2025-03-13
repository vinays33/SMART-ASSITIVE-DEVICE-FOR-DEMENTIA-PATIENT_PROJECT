# Smart Assistive Device for Dementia Patients

## Overview
The **Smart Assistive Device for Dementia Patients** is a **wearable device** designed to enhance patient safety by providing **real-time location tracking and health monitoring**. It helps caregivers monitor movement, detect emergencies, and receive alerts when a patient moves outside a predefined safe zone.

### Key Features:
- **GPS Tracking** – Monitors the patient’s real-time location
- **Geo-Fencing Alerts** – Sends notifications if the patient wanders off
- **Health Monitoring** – Tracks heart rate, oxygen levels, and temperature
- **Long-Range Communication** – Uses LoRa technology for low-power, wide-area connectivity
- **Cloud Integration** – Allows remote monitoring through ThingSpeak

### Components Used:
- **Neo 6M GPS Module** – Location tracking
- **MAX30100 SpO2 Sensor** – Oxygen level and heart rate monitoring
- **LM35 Temperature Sensor** – Body temperature tracking
- **ADXL345 Accelerometer** – Fall detection
- **STM32 F411RE & ESP-32 Microcontrollers** – Data processing and cloud communication
- **Ra-02 LoRa Module** – Long-range data transmission
- **0.96” OLED Screen** – Displays real-time data

### Working Principle:
- Sensors collect health and location data.
- GPS verifies if the patient is within a safe zone.
- Alerts are sent to caregivers if the patient moves beyond the boundary.
- Data is displayed on an OLED screen and uploaded to the cloud for remote access.

### Future Enhancements:
- AI-powered health predictions
- Mobile app for real-time notifications
- Extended battery life and two-way communication

This device ensures **patient safety** while reducing **caregiver workload**, making it a valuable tool for dementia patient care.


# 💡 Smart Hall Light (Lab-Constrained Version)

This project provides an implementation for a smart multi-functional hallway lighting system, combining automated illumination, a home security protocol, and a local WiFi dashboard.

## ⚙️ Operating Modes

The system operates in three distinct modes displayed on an LCD, selectable by buttons:

### 1. Motion Detector Mode
* **Trigger:** IR (Infrared) Motion Sensor.
* **Behavior:** Activates the LED when movement is detected and keeps it on for a predefined period.
* **Energy Saving:** Utilizes a light sensor to ensure the LED *only* activates if the hallway is dark.

### 2. Guard Mode
* **Trigger:** IR (Infrared) Motion Sensor.
* **Behavior:** When movement is detected, a buzzer is activated to deter intruders. A disable button is provided to shut the alarm off.
* **Alerts:** The intruder detection status is logged and displayed on the local web dashboard. 

### 3. Manual Mode
* **Behavior:** Simple override to manually toggle the LED ON or OFF.

## 🛠️ Components
* [ ] **WiFi Module**
* [ ] **Control Buttons**
* [ ] **LED**
* [ ] **IR Sensor**
* [ ] **Photoresistor**
* [ ] **Buzzer**
* [ ] **LCD**

# 💡 Smart Hall Light

A conceptual design for a smart, multi-functional hallway lighting system. This project combines automated illumination, basic home security, and remote control into a single IoT device.

## ⚙️ Operating Modes

The system operates in three distinct modes, selectable remotely via WiFi:

### 1. Motion Detector Mode (Auto-Illumination)
*   **Trigger:** Infrared (IR) Sensor.
*   **Behavior:** Activates the LED when movement is detected and keeps it on for a predefined period.
*   **Energy Saving:** Utilizes an ambient light sensor to ensure the LED *only* activates if the hallway is dark.

### 2. Guard Mode (Security)
*   **Trigger:** Passive Infrared (PIR/IR) Sensor.
*   **Behavior:** When movement is detected, a buzzer is activated to deter intruders.
*   **Alerts:** Sends a notification message via WiFi to the user.
*   **Deactivation:** The buzzer can be turned off remotely, or it will shut off automatically after a set duration.

### 3. Manual Mode
*   **Behavior:** Simple remote override to manually toggle the LED ON or OFF via the WiFi interface, bypassing sensor inputs.

---

## 🛠️ Hardware Components

Here is the proposed bill of materials for this build:

*   [ ] **Microcontroller:** WiFi-enabled board (e.g., ESP8266, ESP32)
*   [ ] **Light Source:** LED (or LED strip + relay/MOSFET)
*   [ ] **Motion Sensor:** IR / PIR Sensor
*   [ ] **Light Sensor:** Photoresistor (LDR) or digital light sensor module
*   [ ] **Alarm:** Active or passive buzzer
*   [ ] **Display (Optional):** LCD or OLED screen to display the current active mode and network status

---

## 🚀 Next Steps (To-Do)
- [ ] Select specific microcontroller model (ESP32 recommended for WiFi capabilities).
- [ ] Draft the circuit wiring diagram.
- [ ] Develop the web server or app integration for mode selection and notifications.

# 🌿 Smart Irrigation System Using ESP32 & Blynk App

An IoT-based automation project for intelligent irrigation monitoring and control using the ESP32 microcontroller and the Blynk IoT platform.

---
<img width="650" height="827" alt="image" src="https://github.com/user-attachments/assets/08ba8ba6-14c5-46f5-9dcd-af67b3764e74" />
## 📜 Summary

The **Smart Irrigation System** leverages the power of IoT to automate watering based on real-time environmental data. It uses an **ESP32 board** connected to **soil moisture**, **water level**, and **temperature & humidity (DHT22)** sensors. A **relay module** controls the water pump, and an **RGB LED strip** provides visual feedback.

This system supports two modes:
- **Automatic Mode**: Activates irrigation when soil moisture falls below a threshold.
- **Manual Mode**: Lets users control the pump via the **Blynk app**.

The **Blynk app** also displays:
- Soil Moisture %
- Water Level
- Temperature & Humidity

This project is ideal for farms, gardens, and small-scale agriculture setups.

---
<img width="1092" height="487" alt="image" src="https://github.com/user-attachments/assets/5adeb372-1a07-4a30-8f24-f8fbe82702fb" />




## 🧰 Components Used

| Component                  | Quantity |
|---------------------------|----------|
| ESP32 Board               | 1        |
| Capacitive Soil Moisture Sensor | 1 |
| Water Level Sensor        | 1        |
| DHT22 Sensor              | 1        |
| Water Pump                | 1        |
| Relay Module              | 1        |
| 3.7V Li-ion Battery       | 1        |
| 5V RGB LED Strip          | 1        |
| Jumper Wires              | As needed |

---

## 📱 Features

- 🌡️ Real-time monitoring of temperature, humidity, soil moisture, and water level  
- 💧 Automatic irrigation when soil is dry  
- 🖲️ Manual pump control via smartphone  
- 🔔 Visual feedback using RGB LED strip  
- 📶 Wireless control and updates using Blynk App  

---

## 📺 Watch the Tutorial

👉 [Watch the Tutorial](#) *(insert your YouTube or project video link here)*

---

## 🚀 Getting Started

1. **Connect the hardware** as per the circuit diagram (to be added or linked).
2. **Flash the ESP32** using Arduino IDE or PlatformIO with the provided source code.
3. **Set up your Blynk App**:
   - Add widgets for moisture, temperature, humidity, and manual control.
   - Paste the auth token into your code.
4. Power the device using the Li-ion battery or USB power bank.

<img width="650" height="831" alt="image" src="https://github.com/user-attachments/assets/a6fa75e7-3a07-4e91-959a-a3cd232f880e" />

---

## 💡 Credits

Inspired by tutorials and support from the maker community & [CircuitDigest](https://circuitdigest.com/).




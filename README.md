# 🚀 TWIN NODE V1.0  
### Ultra-Low Power Water Level Monitoring Node

TWIN NODE V1.0 is a compact, ultra-low power wireless water level monitoring node designed for learning, prototyping, and field experimentation. The system is built around the ESP-12F (ESP8266) and uses a waterproof ultrasonic sensor to measure water levels with high reliability.

---

## 📌 Key Features
- ESP-12F (ESP8266) based design  
- ESP-NOW wireless communication  
- Ultra-low power operation with deep-sleep  
- Battery + solar power ready  
- Waterproof ultrasonic water level sensor  
- Compact PCB size (~65 × 35 mm)  
- DRC & ERC verified schematic  

---

## 🧠 System Overview
The node periodically wakes from deep sleep, powers the ultrasonic sensor, measures the water level, and transmits data wirelessly using ESP-NOW. After transmission, the system returns to deep sleep to minimize power consumption, making it suitable for long-term deployment.

---

## 🔋 Power Architecture
- Li-ion battery support  
- Solar panel input for energy harvesting  
- On-board Li-ion charging IC  
- Low-dropout regulator (LDO) for stable MCU supply  
- Hardware power-pin control to reduce standby losses  

---

## 📡 Communication
- **Protocol:** ESP-NOW  
- **Range:** Short to medium range (environment dependent)  
- **Use Case:** Peer-to-peer sensor node to gateway communication  

---

## 🧩 Hardware Blocks
- ESP-12F (ESP8266)
- Ultrasonic Sensor Interface
- Li-ion Battery Charger
- Solar Input & Power Path
- Protection Circuitry
- Boot Configuration Network
- I/O Expansion Header

---

## 🛠️ Design Status
- **Version:** V1.0  
- **Status:** Schematic complete  
- **Checks:** DRC & ERC passed  
- **Fabrication:** Planned at Lion Circuits  

---

## 🔄 Future Improvements (V2.0)
- Optimized component placement  
- Improved PCB aesthetics  
- Further reduction in power consumption  
- Mechanical refinements  

---



## 🎯 Applications
- Water tank level monitoring  
- Smart irrigation systems  
- Remote level sensing  
- IoT learning & prototyping  

---

## 👨‍💻 Designed By
**Harsh Saini**  
Electronics & Hardware Design Engineer  

---

## 📜 License
This project is intended for educational and prototyping purposes.  
Feel free to modify and improve with proper attribution.

---

⭐ If you find this project useful, consider giving it a star!

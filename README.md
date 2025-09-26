# Megasonic_Sumo_Robot
# National Sumo Robotics Competition 2025 🥋🤖 

## 📌 Overview  
This repository contains the code and design files for our **Megasonic Sumo Robot**, built to compete in the **National Sumo Robot Competition 2025**.  
The robot is designed to detect ring boundaries, locate opponents, and push them out of the arena using autonomous strategies.

---

## ⚙️ Features  
- ✅ Autonomous opponent detection using time of flight sensor.   
- ✅ Edge detection to prevent the robot from leaving the ring using line sensor.
- ✅ Low center of mass for better stability.
- ✅ Custom made wheels with higher quality to fit the custom made robot body.
- ✅ Proffessional PCB design and cable management.
- ✅ Blade strategic placement.
- ✅ Modular codebase for easy adjustments.
- ✅ Image processing for more accurate line detection.
- ✅ Custom designed gear system to accommodate the motors within the required dimensions.

---

## ⚙️ Mechnical  
- ### **Motor Choice**
  The chosen motor is **wg960** and it was chosen for the following factors:
    -  Very powerful (at 60 Whats its much more powerful than your typical sumo motor).
    -  Very efficient.
    -  

- ### **Robot Body**
Arduino / Raspberry Pi / ESP32  
- ### **Gear Box**
Arduino / Raspberry Pi / ESP32  
- ### **Wheels**
Arduino / Raspberry Pi / ESP32  
- ### **Blades**
Arduino / Raspberry Pi / ESP32
- ### **Stability**
Arduino / Raspberry Pi / ESP32 

---

## 🛠️ Hardware  
- **Microcontroller**: Arduino / Raspberry Pi / ESP32  
- **Motors**: High-torque DC motors with motor driver  
- **Sensors**: IR edge detection, ultrasonic for opponent detection  
- **Frame**: Lightweight custom chassis  
- **Power**: LiPo battery (11.1V recommended)  

---

## 💻 Programming & Strategy  
- **Header Files**: Python / C++
- **I2C protocol**: Python / C++
- **Image Processing**: Python / C++  
- **Unit Testing**:  
  - Arduino motor/sensor libraries  
  - OpenCV (if camera-based detection is used)
 
---

## ⚡ELECTRONICS
- **Cable Management**: Python / C++
- **Power electronics and protection**: Python / C++
- **Driver Choice**: Python / C++  
- **PCB**:  
  - Arduino motor/sensor libraries  
  - OpenCV (if camera-based detection is used)  

### 🔑 Logic  
1. **Edge Detection** → If the white border is detected, step back and rotate 180°.  
2. **Opponent Detection** → Charge forward aggressively.  
3. **Fallback** → Continuous scanning until match ends.  

---

## 🚀 How It Works  
1. Robot scans the arena for opponents.  
2. Edge detection prevents exiting the ring.  
3. Opponent detection activates the attack mode.  
4. Repeats until the round is over.  

---

## 📷 Media  
📸 *Add pictures, GIFs, or videos of the robot here (build process, testing, or competition day).*  

---

## 🏆 Competition  
- **Event**: National Sumo Robot Competition 2025  
- **Location**: Jordan  
- **Team Name**: *[Insert Team Name]*  
- **Status**: Competing on *[Insert Date]*  

---

## 👥 Team  
- Built by: **[Fiancé’s Name]**  
- Supported by: **[Your Name, if you helped]**  

---

## 📄 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

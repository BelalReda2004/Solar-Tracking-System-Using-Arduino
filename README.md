# ☀️ Dual Axis Solar Tracking System

## 📖 Overview
This project showcases a **Dual Axis Solar Tracking System** designed to optimize the orientation of solar panels by automatically adjusting both the **azimuth (horizontal)** and **elevation (vertical)** angles. By following the sun throughout the day, the system maximizes sunlight exposure, improving the overall energy output compared to fixed or single-axis systems.

---

## ⚙️ Features

- 📈 **Increased Efficiency** – Boosts energy capture by up to **40%** over fixed systems
- 🌥 **Low-Light Optimization** – Continuously adjusts to detect the optimal light source
- 💰 **Improved ROI** – Generates more energy with better long-term returns
- 🧠 **Smart Control** – Sensor-driven tracking for precise orientation
- 📐 **Space-Efficient** – Maximizes performance in limited installation areas

---

## 🧰 Components Used

| Component            | Description                                   |
|----------------------|-----------------------------------------------|
| **Solar Panels**     | Convert solar energy into electricity         |
| **Arduino (Nano/UNO)** | Microcontroller to control tracking logic     |
| **LDR Sensors**      | Detect sunlight intensity and direction       |
| **Servo Motors**     | Control dual-axis movement                    |
| **Mounting Structure** | Holds and moves the solar panel               |
| **Resistors**        | Used with LDRs for analog light sensing       |
| **Power Source**     | USB or battery for Arduino and motors         |
| **Wires & Breadboard** | Circuit prototyping and connectivity         |

---

## 🛠️ Construction Steps

1. **Frame Design** – Build a mounting structure allowing free movement in both axes.
2. **Install Motors** – Attach servo motors for tilt (vertical) and rotation (horizontal).
3. **Sensor Placement** – Arrange LDRs in a cross pattern to detect sun position accurately.
4. **Program Arduino** – Implement logic to adjust motor angles based on LDR feedback.
5. **Assemble & Test** – Connect all parts, upload the code, and test the tracking behavior.

---

## 🔁 How It Works

- Four LDR sensors are placed around the panel.
- The Arduino reads the light intensity on each LDR.
- Based on the difference in values, the code adjusts servo motor angles to move the panel toward the light source.
- The system continuously monitors light direction and realigns accordingly.

---

## 🌱 Benefits

- ✅ **Optimized Solar Energy Absorption**
- ✅ **Environmentally Friendly**
- ✅ **Long-Term Cost Savings**
- ✅ **Perfect for Educational and Real-World Applications**
- ✅ **Scalable to Industrial or Commercial Solar Farms**

---

## 🚀 Future Improvements

- 📊 Add data logging with an **SD Card Module**
- 🌦 Integrate **weather sensors** for intelligent shutdown during clouds or rain
- 🌐 Connect to an **IoT platform** for remote monitoring and control

---

## 📎 Tools & Software

- 💻 **Arduino IDE** – Code development and upload
- 🧩 **Proteus / Tinkercad** – (Optional) Circuit simulation
- 🧰 **Basic Tools** – Screwdrivers, frame materials, etc.

---

## 📸 Project Preview

<img width="1163" height="683" alt="Simulation" src="https://github.com/user-attachments/assets/8097ba5c-a2ff-4dd8-9bb3-9562b8c27461" />


---

## 📚 Educational Value

This project is a **great introduction to renewable energy systems**, combining **electronics**, **sensors**, **motor control**, and **automation** in one practical build. It's ideal for:
- Engineering students
- IoT or renewable energy enthusiasts
- Solar system prototyping

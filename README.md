# 🤖 Autonomous Quadruped Robot Platform

A modular, 3D‑printed **quadruped robot platform** designed from scratch to bridge **precision mechanical CAD** with **real-world mechatronic integration**.  
This project focuses on *first‑time‑right* assembly, modular architecture, and design for manufacturability (DFMA). 

---

## 🎯 Aim

> To design and engineer a **modular, multi‑legged robot** from scratch, combining high‑fidelity CAD modelling with practical electronics integration and prototyping.

Core goals:
- Build a **mechanically robust** chassis and leg system suitable for 3D printing 🧩 
- Ensure **zero‑shim, first‑time‑right assembly** via tolerance stack‑up analysis 📏
- Design a layout that cleanly integrates **electronics, wiring, and power** without clashes 🔌 
- Keep the platform **modular and scalable** for future control / gait experiments 🧠 

---

## 🧰 Tech Stack

### 🖥️ Software & CAD

- **Siemens NX** – structural components and refined assemblies
- **CATIA V5** – precision part modeling, GD&T, and assembly checks 
- **SolidWorks** – parametric modelling and alternative design iterations 
- **Core methods**:  
  - GD&T  
  - DFMA  
  - Tolerance stack‑up  
  - 3D‑print‑oriented design 
---

## 🔩 Hardware & Electronics

- **Controller:** ESP32 microcontroller board ⚙️
- **Actuators:** MG90S micro servo motors (multi‑joint leg actuation) 🦴
- **Driver board:** PCA9685 16‑channel servo driver for coordinated leg control 🧠 
- **Power stage:**
  - MP1584 step‑down (buck) converter for regulated supply
  - **2× 18650 Li‑ion cells** as the main battery pack 🔋

Mechanical structure:
- 3D‑printed chassis and leg segments optimised for **FDM printing** 🧱
- Parametric part‑family models to scale the robot for different payloads 🧮

---

## 🧠 Skills Demonstrated

### Mechanical & CAD 🛠️

- Full CAD pipeline: from **concept sketch → 3D parts → assemblies → drawings** 
- **Tolerance stack‑up analysis** to avoid binding / excessive play in joints 
- **Parametric modelling** of leg and body segments for quick design changes 
- **DFMA**: parts shaped and oriented for FDM printing, support‑minimised geometry

### Mechatronics & Integration 🔌

- Component selection and packaging for:
  - ESP32
  - PCA9685
  - Servos
  - MP1584
  - Battery pack
- Mechanical design of:
  - **Mounting bosses** and brackets
  - Cable routing paths
  - Clearance zones for moving linkages 

### Prototyping & Validation 🧪

- Iterative 3D‑printed prototypes to verify:
  - Fit and tolerance
  - Servo range and link motion
  - Structural behaviour under expected load 
- Adjustments based on assembly feedback to improve robustness and ease of build 

---

## ⭐ Key Features

- **Zero‑shim assembly**  
  Designed with proper tolerance stack‑up so the first build fits together without additional shimming or rework.

- **Modular architecture**  
  - Parametric chassis that can be resized for different payloads  
  - Leg modules designed as repeatable units for 4‑leg (or extended) configurations. 

- **DFMA‑driven 3D‑print design**  
  - Parts oriented and shaped to print reliably on consumer FDM printers  
  - Reduced supports, smart part splits, and consistent wall thicknesses.

- **Electronics‑aware CAD**  
  - Dedicated pockets and mounts for ESP32, PCA9685 and power electronics  
  - Protected, planned cable paths to avoid interference with joints and ground clearance. 

- **Future‑ready platform**  
  Mechanical and electrical architecture built so control algorithms, gait generation, and sensing can be added later without redesigning the whole robot.

---

## 🚀 Next Steps / Possible Extensions

- Add **inverse kinematics & gait control** on the ESP32 🎛️
- Integrate **IMU + foot contact sensors** for stability experiments 🦿
- Run **basic FEA** on leg segments to validate safety factors under dynamic loading 📊

---

## Author 👨‍💻

**Atharv Nitin Agashe**  
Mechanical Design Engineer · M.Sc. Mechatronics & Robotics  
- Email: `atharvagashe962001@gmail.com`  
- LinkedIn: [www.linkedin.com/in/atharv-agashe9601](https://www.linkedin.com/in/atharv-agashe9601)


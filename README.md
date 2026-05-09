# AUTONOMOUS QUADRUPED ROBOT PLATFORM 🐾🤖

## 1. Overview

The **Autonomous Quadruped Robot Platform** is a 4‑legged walking robot designed to explore legged locomotion, basic autonomy, and mechanically robust joint design.  
The project focuses on **CAD modelling of the full mechanical structure**, including links, joints, body frame, and actuation interfaces.

---

## 2. Aim 🎯

- Design a **quadruped robot chassis** with four legs, each providing multiple degrees of freedom for walking gaits.  
- Develop a **parametric CAD assembly** that allows easy changes to dimensions, link lengths, and actuator choices.  
- Ensure the structure is reasonably **lightweight and manufacturable** using common workshop tools and materials.

---

## 3. Tech Stack & Tools 🧰

### Software

- 3D CAD: **Siemens NX / Fusion 360 / SolidWorks **

### Core Skills

- Multi‑body mechanism design in CAD.  
- Parametric modelling of links, brackets, and body.  
- Assembly constraints, joint definition, and basic motion checks.  
- Creation of **2D drawings, exploded views, and BOMs**.

---

## 4. Mechanical Architecture 🧩

- **Main body / chassis**  
  - Central frame that houses electronics, battery, and controllers.  
  - Mounting points for legs and cable routing paths planned in CAD.

- **Leg structure (hip, thigh, shank)**  
  - Each leg modelled as a series of rigid links connected by revolute joints.  
  - Hole patterns and interfaces designed for servo/actuator mounting.

- **Actuator mounts and brackets**  
  - Custom brackets created to adapt standard servo/motor geometries to the leg links.  
  - Clearance around horns and arms checked in the CAD assembly.

- **Feet / end-effectors**  
  - Simple foot pads designed for grip and stability.  
  - Geometry kept modular so different foot designs can be tested later.

---

## 5. Modelling Workflow 🧱

1. **Define leg kinematics and DOF**  
   - Decide hip and knee joint layout and approximate range of motion.  
   - Fix reference dimensions like body size, leg length, and stance width.

2. **Part modelling**  
   - Create individual CAD parts for body plates, leg links, brackets, and feet.  
   - Use **parametric dimensions** so changes in length or thickness update the assembly.

3. **Assembly & motion check**  
   - Assemble all components with appropriate mates/joints.  
   - Run basic motion in CAD to verify:
     - No interference between links.  
     - Sufficient clearance for actuators and wiring.

4. **Detailing**  
   - Generate **2D detail drawings** for manufacturing.  
   - Prepare an **exploded view** and **BOM** for all major components.

---

## 6. Key Features & CAD Highlights 🌟

- **Fully parametric leg design**  
  - Link lengths, offsets, and mounting holes driven by dimensions that can be easily tuned.

- **Assembly‑ready geometry**  
  - Parts designed for laser cutting, 3D printing, or simple machining.  
  - Fastener sizes and hole patterns chosen to match standard hardware.

- **Clear actuator integration**  
  - CAD models include servo/motor envelopes to avoid collisions.  
  - Brackets designed around realistic component dimensions.

- **Documentation‑focused**  
  - Clean drawings, exploded views, and labelled subassemblies suitable for a **CAD portfolio** or manufacturing hand‑off.

---

## 7. Possible Extensions 🚀

- Refine **cable management and mounting points** once electronics are finalised.  
- Add alternative leg variants (e.g., different link lengths or foot designs) using the same parametric base model.  
- Create simple **rendered views** of walking poses for presentations and portfolio use.

---

## 8. Author 👨‍💻

**Atharv Nitin Agashe**  
Mechanical Design Engineer · M.Sc. Mechatronics & Robotics  
- Email: `atharvagashe962001@gmail.com`  
- LinkedIn: [www.linkedin.com/in/atharv-agashe9601](https://www.linkedin.com/in/atharv-agashe9601)

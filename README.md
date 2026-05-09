
# 🤖 Autonomous Quadruped Robot Platform

![CAD Design](renders/quadruped_render.png)

> A fully designed autonomous quadruped robot platform developed as part of an M.Sc. Mechatronics & Robotics project,
> focusing on multi-body mechanical design, joint kinematics, and structural integrity for legged locomotion.

---

## 🎯 Aim

The aim of this project is to design and develop a **mechanically robust quadruped (4-legged) robot platform**
capable of stable locomotion over uneven terrain. The focus is on:

- Designing a lightweight yet rigid body frame suitable for dynamic walking gaits
- Engineering leg assemblies with sufficient Degrees of Freedom (DOF) for natural motion
- Creating a fully parametric CAD model ready for prototyping and manufacturing
- Laying the mechanical foundation for future integration of sensors and autonomous control systems

---

## 🛠️ Skills Demonstrated

| Skill | Tool / Method |
|---|---|
| 3D CAD Modeling & Assembly | Siemens NX / Fusion 360 |
| Multi-body mechanical design | Joint constraints, motion simulation |
| Structural analysis | FEA-based stress evaluation on leg links |
| Technical drawing generation | 2D engineering drawings with GD&T |
| Design for Manufacturing (DfM) | Material selection, tolerance planning |
| Kinematics & motion planning | Forward kinematics of 3-DOF leg structure |
| Parametric modeling | Fully parametric design for easy iteration |

---

## ⚙️ Components Used

### Mechanical Structure
- **Body Frame** — Lightweight aluminium/ABS structural chassis, designed for load distribution
- **Leg Assembly (×4)** — Each leg consists of 3 rigid links: Coxa, Femur, and Tibia
- **Joints** — 3 revolute joints per leg = **12 DOF total** across the platform
- **End Effector (Foot)** — Curved foot tip designed for grip on irregular surfaces
- **Fasteners & Brackets** — M3/M4 bolts, custom-designed mounting brackets

### Actuation (Design Provision)
- **Servo Motor Mounts (×12)** — Designed to house standard hobby/industrial servo motors
- **Servo Horn Interface** — Direct-drive coupling between servo output shaft and joint link

### Electronics Provision (Structural Mounts Designed)
- Mounting slots for **microcontroller board** (e.g., Raspberry Pi / STM32)
- Cable routing channels integrated into frame design
- Battery bay designed for center-of-mass optimization

---

## ✨ Key Features

- **12-DOF Leg Architecture** — 3 DOF per leg allows complex gait patterns including trot, crawl, and wave gait
- **Symmetrical Body Design** — Balanced weight distribution for stable static and dynamic posture
- **Modular Leg Assembly** — Each leg is independently detachable for maintenance and iterative redesign
- **Parametric CAD Model** — All dimensions driven by parameters; easily scalable for different payload requirements
- **DfM-Ready Design** — Designed with real manufacturing constraints in mind (3D printing + CNC machining)
- **Center of Mass Optimization** — Battery and electronics bay positioned at geometric center to maximize stability
- **Collision-Free Joint Range** — Joint travel limits designed to prevent self-collision during extreme poses

---


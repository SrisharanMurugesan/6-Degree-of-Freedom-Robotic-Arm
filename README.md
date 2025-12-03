# 6-DOF-Robotic-Arm

<img width="318" height="483" alt="Image" src="https://github.com/user-attachments/assets/8913a520-c5ba-44ff-9732-2c5dba36801d" />

## Description

A fully engineered **6-degree-of-freedom robotic arm** designed around three servo-driven joints for 6-degree motion. This project includes complete CAD files of a fully functional arm with mechanical grippers. The base contains a dedicated compartment for mounting a microcontroller, along with cable pass-through paths that run through the tower and to each servo. All parts are modeled with appropriate tolerances so that once printed, lightly sanded, and cleaned, the arm assembles smoothly with no adjustment. The design focuses on stability, modularity, and ease of construction, making it suitable for demonstrations, education, and lightweight pick-and-place experimentation.

---

## Mechanical Overview

Actuation:

- 3 × active servos (base rotation, shoulder, elbow)  

Structure:

- Multi-segment arm with servo mounts  
- Internal wire-routing channels inside every segment  
- M3 hardware for base mountage
- Press fit connections for arm 

Gripper:

- Parallel mechanical gripper  
- Gear-linked fingertip motion  

Base:

- Hollow structure for microcontroller mounting within base 
- Bolt hole for securing to a table or platform  

---

## Tolerances & Fits (A1 specific)

- Use **+0.15 mm** clearance for high-accuracy parts or slow-speed prints  
- Use **+0.20–0.25 mm** clearance for moving joints, pins, or fast prints  
- Screw/glue joints are reliable at **+0.15 mm**  
- Moving joints with friction should be **+0.20–0.25 mm**  
- Avoid going above +0.30 mm unless intentionally creating loose pivots

If your printer overshoots or undershoots hole sizes, adjust tolerances by **±0.05 mm**.

---

## Recommended Materials

- **PLA+:** Highest dimensional accuracy  
- **PETG:** Flexible and impact-resistant  
- **Nylon:** Ideal for gears or high-wear parts  
- **Metal rods:** Recommended for pivot pins  

Electronics:

- 3 × MG90S or MG996R 9 gram servos  
- Arduino Nano / Uno / ESP32  
- External 5V 2–3A power supply  
- Servo extension wires and M3 bolts  

---

## Bambu Lab A1 Print Settings (PLA)

- Layer Height: **0.16–0.20 mm**  
- Nozzle: **0.4 mm**   
- Top/Bottom: **6–8 layers**  
- Infill:  
  - Structural parts: **30–40% gyroid**  
  - Small brackets: **20–25%**  
- Supports: **Build-plate-only**  
- Brim: **5–8 mm** on tall slender joints  
- Speed: **A1 Standard** preset

---
## Author's Note

This arm supports a wide range of uses. I wired mine to an Arduino and programmed the servos so it could act as a third-arm during soldering and assembly work. The exact behavior of the arm can be customized based on personal preference and code modifications, allowing users to adapt it for whatever they desire.

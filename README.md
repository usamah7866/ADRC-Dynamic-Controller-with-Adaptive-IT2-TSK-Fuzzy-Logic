# ADRC Dynamic Controller with Adaptive IT2-TSK Fuzzy Logic

This repository contains a MATLAB implementation of an **Active Disturbance Rejection Control (ADRC)** scheme enhanced with an **Adaptive Interval Type-2 Takagi–Sugeno–Kang (IT2-TSK) Fuzzy Logic Controller** for trajectory tracking of a differential drive mobile robot.

The controller is designed to handle model uncertainties and external disturbances while maintaining accurate trajectory tracking performance.

---

## 📌 Features
- **Differential Drive Robot Kinematics** for computing linear and angular velocities.
- **ADRC with Extended State Observer (ESO)** to estimate and compensate disturbances in real time.
- **Adaptive IT2-TSK Fuzzy Logic** for dynamic gain tuning and nonlinear control.
- Simulation of **circular trajectory tracking**.
- Performance evaluation under **sinusoidal and nonlinear disturbances**.

---

## 📂 Repository Structure
- `main.m` → Main MATLAB script implementing the full controller and simulation.
- `plots/` → (Optional) Folder for generated trajectory and control response plots.
- `docs/` → (Optional) Folder for extended documentation or notes.

---

## ⚙️ Requirements
- MATLAB **R2021a or later** (may also work with earlier versions).
- **Fuzzy Logic Toolbox** (for fuzzy controller implementation).
- **Control System Toolbox** (for additional analysis, optional).

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/adrc-it2tsk-controller.git
   cd adrc-it2tsk-controller
2. Open MATLAB and navigate to the repository folder.

3. Run the main script:

4. View simulation results including:

Robot trajectory vs. reference trajectory

Tracking error plots

Control signal responses

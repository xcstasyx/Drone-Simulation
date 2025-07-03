# Simulink Drone Project 🚁

This repository contains a MATLAB Simulink model of a multirotor drone, including its control system and flight dynamics.

## 📦 Project Contents

- `models/`: Simulink `.slx` files for the drone plant and flight controller
- `images/`: Block diagram and simulation snapshots
- `docs/`: Optional technical report, system description, or slides
- `README.md`: Documentation for setup and usage

## 🧠 Features

- PID-based flight controller
- Simulated IMU feedback
- Motor mixing logic
- 3D plant model (rigid-body dynamics)
- Adjustable inputs for manual or autonomous flight modes

## 🛠 Requirements

- MATLAB R2023a or later
- Simulink
- Simscape (optional, if physics modeling used)

## ▶️ How to Run

1. Open `quadcopter_model.slx` in MATLAB Simulink
2. Configure simulation time and parameters
3. Click **Run**
4. Observe output scopes or 3D simulation (if enabled)

## 📸 Preview

![Simulink block diagram](images/simulink_block_diagram.png)

## 📜 License

[MIT License](LICENSE)

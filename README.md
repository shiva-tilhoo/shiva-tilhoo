# Shiva Tilhoo

Engineering student at ECE Paris, Embedded Systems major.
I enjoy systems where software meets hardware: real-time firmware, mobile robotics and physical simulation.

## Projects

### [ECEPILOT — Autonomous ESP32 rover with micro-ROS and SLAM](https://github.com/shiva-tilhoo/ecepilot-autonomous-robot)

A rover that maps a corridor with a 2D LiDAR and drives through it by itself. Multitasking ESP32 firmware (FreeRTOS), micro-ROS link over Wi-Fi, SLAM Toolbox and a 2D simulator on the ROS 2 side, remote-control PCB designed in KiCad.
`C++` `Python` `ESP32` `FreeRTOS` `ROS 2 Humble` `micro-ROS` `SLAM Toolbox` `KiCad` · team project (3)

### [Quantum gate calibration with reinforcement learning](https://github.com/shiva-tilhoo/quantum-gate-calibration-rl)

An RL agent corrects the control pulses of a CZ gate on two noisy superconducting qubits: the average fidelity goes from 0.963 (optimal control alone) to above 0.998. I built the quantum simulator and the interface between the physics and the agents.
`Python` `QuTiP` `Gymnasium` `Stable-Baselines3` `GRAPE` · team project (6)

### [Quoridor in C](https://github.com/shiva-tilhoo/quoridor-c)

The Quoridor board game in the console, for 2 or 4 players, with save/resume, scores and history. Modular code built with CMake.
`C` `CMake` · team project

## Technologies used in these projects

| Area | Tools |
|---|---|
| Embedded | C, C++, ESP32, ATmega328P, FreeRTOS, PlatformIO, I²C, UART |
| Robotics | ROS 2 Humble, micro-ROS, SLAM Toolbox, Nav2, RViz |
| Scientific computing | Python, NumPy, QuTiP, Stable-Baselines3, Matplotlib |
| Tooling | Git, CMake, KiCad, Linux |

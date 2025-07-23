# VTOL-Tailsitter-Unity-SIL
Unity-based VTOL tailsitter simulation for SIL testing, autonomous flight algorithm validation (digital twin), and synthetic test dataset generation.

## Electronics Setup

The VTOL tailsitter UAV uses the following electronic components for control during hover:
- **Two Fixed Motors**: Generate thrust and differential forces for yaw control.
- **Elevons**: Provide pitch and roll moments through deflections for stability.
- **Microcontroller and Sensors**: Enable real-time attitude and position feedback.
- **Communication Loop**: Integrates the control system with the physical prototype for testing 

## Unity Simulation

The Unity-based simulation visualizes the VTOL tailsitter’s flight paths, including rectangular and circular trajectories, to validate autonomous flight algorithms in a digital twin environment 

## Future Work

Future efforts will leverage the Unity simulation to generate synthetic datasets, such as 10,000 episodes, for developing machine learning-based control algorithms. These efforts aim to enhance autonomous flight capabilities—potentially incorporating Vision Language Action Models (VLMs)—toward an intelligent, adaptive VTOL system- Embodied AI.


---

## Media Gallery - Quick Preview

| Force Visualization | Flight Simulation |
|---------------------|-------------------|
| ![force2-](https://github.com/JeffrinSam/VTOL-Tailsitter-Unity-SIL/raw/8d9b2e7512377c32a7a4feba88897cc35028c423/Media/force2-.gif) | ![vtol](https://github.com/JeffrinSam/VTOL-Tailsitter-Unity-SIL/raw/8d9b2e7512377c32a7a4feba88897cc35028c423/Media/vtol.gif) |

# SHM-Live-Visualizer

Interactive Simple Harmonic Motion (SHM) simulation and live analysis dashboard featuring real-time visualization of displacement, velocity, acceleration, energy exchange, phase portraits, and CSV data export.

## Overview

SHM-Live-Visualizer is an interactive scientific application developed for the analysis and visualization of **Simple Harmonic Motion (SHM)** in both simulated and real-world environments. The project provides a comprehensive dashboard for monitoring oscillatory systems through dynamic plots, live parameter tracking, and energy analysis.

The repository contains three modules:

1. **Demo Mode**

   * Simulates SHM using generated values.
   * Useful for testing and demonstrating the application's visualization capabilities.

2. **Live Visualizer**

   * Performs real-time analysis of one-dimensional (1D) vertical oscillations.
   * Receives live sensor data and visualizes displacement, velocity, acceleration, energy exchange, and phase-space behavior.

3. **Raspberry Pi Data Acquisition Module**

   * Acquires sensor data from a Raspberry Pi mounted at the base of the oscillating object.
   * Transmits the collected data to the Live Visualizer for real-time processing and analysis.

## Features

* Real-time SHM simulation and visualization
* Live sensor data acquisition using Raspberry Pi
* Displacement vs Time visualization
* Velocity vs Time visualization
* Acceleration computation and monitoring
* Energy Exchange analysis:

  * Kinetic Energy (KE)
  * Potential Energy (PE)
  * Total Energy (TE)
* Phase Portrait (Displacement vs Velocity)
* Live parameter monitoring panel
* Adjustable simulation settings
* Screenshot capture
* CSV data export
* Dark-themed interactive GUI

## Live Parameters

The dashboard continuously displays:

* Displacement
* Velocity
* Acceleration
* Phase Angle
* Restoring Force
* Time Period
* Amplitude
* Frequency
* Angular Frequency
* Kinetic Energy (KE)
* Potential Energy (PE)
* Total Energy (TE)
* Energy Dissipation Rate
* Maximum Potential Energy
* Maximum Kinetic Energy

## Technologies Used

* Python
* PyQt5
* PyQtGraph
* NumPy
* PySerial
* Raspberry Pi
* Jupyter Notebook

## Project Structure

```text
SHM-Live-Visualizer/
│
├── SHM Visualizer with Generated Values (for Demo).ipynb
├── SHM Visualizer with Live Values.ipynb
├── Raspberry Pi Data Acquisition Code.py
├── README.md
└── .gitignore
```

## Author

**Sanjay Karthik**

Semester 5 B.Sc. Internal Evaluation Project

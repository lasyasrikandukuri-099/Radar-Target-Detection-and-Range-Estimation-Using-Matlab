# Radar Target Detection and Range Simulation Using MATLAB

## 📡 Project Overview

This project implements a **Radar Target Detection and Range Simulation using MATLAB**. The simulation demonstrates how a radar system transmits a signal, receives the echo reflected from a target, and estimates the target's **range and detection characteristics** using digital signal processing techniques.

The project focuses on fundamental radar and signal-processing concepts such as **radar waveform generation, time delay, target echo modeling, noise addition, matched filtering, correlation, and range estimation**.

## 🎯 Objectives

* Generate a radar transmit waveform using MATLAB.
* Model a target at a specified distance.
* Simulate the time delay caused by target range.
* Generate the received target echo.
* Add noise to represent realistic radar conditions.
* Detect the target using correlation/matched filtering.
* Estimate the target range from the detected echo.
* Visualize transmitted, received, and processed signals.
* Study the effect of noise and signal-processing parameters on detection performance.

## 🛰️ Radar Principle

The radar transmits an electromagnetic signal toward a target. When the signal reaches the target, a portion of the energy is reflected back toward the radar.

The target range is calculated from the measured round-trip propagation time:

[
R = \frac{cT_d}{2}
]

where:

* (R) = Target range in meters
* (c) = Speed of light ((3 \times 10^8) m/s)
* (T_d) = Round-trip time delay

The factor of **2** accounts for the signal traveling from the radar to the target and back.

## 🧠 Signal Processing Workflow

```text
Radar Waveform Generation
          ↓
     Target Modeling
          ↓
      Time Delay
          ↓
     Echo Generation
          ↓
      Noise Addition
          ↓
 Matched Filter / Correlation
          ↓
     Target Detection
          ↓
      Range Estimation
          ↓
     MATLAB Visualization
```

## 🛠️ Technologies Used

* **MATLAB**
* Digital Signal Processing
* Radar Signal Processing
* Correlation / Matched Filtering
* Signal Detection
* Range Estimation
* MATLAB plotting and visualization

## 📂 Suggested Project Structure

```text
Radar-Target-Detection-Range-Simulation/
│
├── README.md
│
├── src/
│   ├── radar_simulation.m
│   ├── waveform_generation.m
│   ├── target_echo.m
│   └── range_detection.m
│
├── results/
│   ├── transmitted_signal.png
│   ├── received_signal.png
│   └── range_detection.png
│
└── docs/
    └── project_report.pdf
```

## ▶️ How to Run

1. Install MATLAB.
2. Clone or download this repository.
3. Open the project folder in MATLAB.
4. Navigate to the `src` directory.
5. Open the main MATLAB script.
6. Run:

```matlab
radar_simulation
```

7. Observe the generated signal and range-detection plots.

## 📊 Expected Results

The simulation should demonstrate:

* Transmitted radar waveform.
* Delayed target echo.
* Noisy received signal.
* Matched-filter/correlation output.
* A prominent detection peak corresponding to the target.
* Estimated target range.

For example, if the target is placed at a known simulated distance, the detected peak should occur at the corresponding delay, allowing MATLAB to estimate the target range.

## 🔬 Key Concepts Demonstrated

### 1. Radar Waveform Generation

A suitable pulse or modulated radar waveform is generated for transmission.

### 2. Target Echo Simulation

The target echo is modeled by delaying and scaling the transmitted signal.

### 3. Noise Modeling

Noise is introduced into the received signal to simulate realistic operating conditions.

### 4. Matched Filtering

A matched filter or correlation operation is used to maximize the detectability of the known radar waveform.

### 5. Range Estimation

The location of the detection peak is converted from time delay into physical distance.

## 🚀 Possible Improvements

The project can be extended by implementing:

* Multiple target detection.
* Moving-target simulation.
* Doppler shift estimation.
* Pulse-Doppler radar.
* FMCW radar range estimation.
* CFAR-based target detection.
* Different SNR conditions.
* False-alarm probability analysis.
* Range-Doppler maps.
* Radar cross-section (RCS) modeling.
* Real-time signal visualization.

## 📚 Applications

Radar target detection and range estimation are fundamental techniques used in:

* Automotive radar
* Air-traffic control
* Military surveillance
* Weather radar
* Autonomous vehicles
* Maritime navigation
* Aerospace systems
* Remote sensing

## 👩‍💻 Author

**Lasyasri**

### Project Type

**MATLAB | Radar Signal Processing | Digital Signal Processing**

---

⭐ If you find this project useful, consider giving the repository a star.

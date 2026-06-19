# Signal Conditioning System for Slip Detection in a Two‑Jaw Robotic Gripper

This repository contains the work for a project in the **Sensing, Instrumentation & Measurement Systems** course.

## Overview
The goal is to design and simulate an analog signal conditioning circuit that processes the output of a piezoelectric sensor to detect slip during robotic grasping. The system amplifies weak millivolt signals, filters out noise (including 50 Hz mains hum), and prepares the signal for analog‑to‑digital conversion. The circuit is simulated in LTspice, and the complete signal chain is modelled in MATLAB with a graphical user interface for calibration and monitoring.

## What’s Included
- **`slip_detection_report.pdf`** – Full project report (English) with all derivations, figures, and results.
- **`slip_detection_report.tex`** – LaTeX source of the report.
- **Figure files** – All images used in the report (schematic, simulation waveforms, frequency response, MATLAB GUI).

## Key Topics
- Piezoelectric sensor modelling
- Instrumentation amplifier design (JFET input, high CMRR)
- Passive band‑pass and notch filters
- LTspice simulation under noisy industrial conditions
- Electromagnetic interference (EMI) and mechanical shock analysis
- A/D and D/A conversion simulation (PSpice)
- System‑level modelling and GUI in MATLAB

## Tools Used
- **LTspice** – Analog circuit simulation
- **PSpice** – A/D and D/A converter simulation
- **MATLAB** – System modelling, slip detection algorithm, GUI
- **LaTeX** – Report writing

## Authors
- Mohammad Mahdi Barzegar
- Mohammad Reza Mahdavi
- Mohammad Moein Abolfathi

Course: Sensing, Instrumentation & Measurement Systems - Prof. Jahed - Electrical Engineering Department, Sharif University of Technology
Date: February 2026

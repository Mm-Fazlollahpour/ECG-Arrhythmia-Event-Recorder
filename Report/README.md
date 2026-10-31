# Bachelor's Thesis – Technical Report

## Real-Time Cardiac Arrhythmia Detection Using Machine Learning Algorithms (Event Recorder)

This directory contains the complete bachelor's thesis documenting the design and implementation of an intelligent, wearable ECG event recorder for real-time cardiac arrhythmia detection.

The project was conducted at the **School of Electrical and Computer Engineering, University of Tehran**, with a focus on embedded systems, biomedical signal processing, low-power hardware design, and machine learning.

## Report Contents

The thesis is organized into five main chapters:

### Chapter 1 – Introduction

Introduces the electrical activity of the heart, ECG signal characteristics, and common cardiac arrhythmias, including Premature Ventricular Contractions (PVCs) and Premature Atrial Contractions (PACs).

It also discusses the clinical motivation for continuous ECG monitoring and the objectives of developing an automatic cardiac event recorder.

### Chapter 2 – Literature Review

Reviews previous research on ECG heartbeat classification using deep learning and transfer learning.

The chapter discusses existing approaches and positions the proposed embedded arrhythmia detection system in relation to previous studies.

### Chapter 3 – Hardware Design

Describes the hardware architecture and the major components of the wearable monitoring device, including:

- ESP32-S3 microcontroller
- ECG analog front-end and signal acquisition
- Voltage regulation and power management
- Rechargeable battery and charging circuitry
- USB-to-UART communication interface
- Custom PCB design and assembled development board

### Chapter 4 – Software Implementation

Presents the embedded signal-processing and machine-learning pipeline, including:

- ECG acquisition using the ESP32-S3 ADC
- RTC and Ultra-Low-Power (ULP) processing
- Digital signal preprocessing
- Heartbeat detection and segmentation
- Machine-learning-based arrhythmia classification
- TensorFlow Lite model deployment
- Event-triggered ECG data storage

### Chapter 5 – Conclusion

Summarizes the implemented ECG event recorder, its hardware and software architecture, and the outcomes of the arrhythmia detection approach.

## Technical Documentation

The complete report includes circuit descriptions, system architecture diagrams, ECG signal plots, PCB illustrations, and embedded signal-processing results.

**Available Report:**

[Download the Full Bachelor's Thesis – PDF](BA_Project_Report_English.pdf)

## Academic Information

**Author:** Mohammad Mehdi Fazlollahpour

**Institution:** University of Tehran

**Department:** School of Electrical and Computer Engineering

**Field:** Electrical Engineering – Electronics

**Supervisor:** Dr. Omid Shoaei

**Academic Project:** Bachelor's Thesis

**Year:** 2025

---

*This report presents an academic research and engineering prototype developed for educational and research purposes. It is not intended to serve as a clinically validated medical diagnostic device.*

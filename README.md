# 🌍 NASA Space Apps 2024
**Challenge:** Seismic Detection Across the Solar System

[![NASA Space Apps](https://img.shields.io/badge/NASA-Space%20Apps%202024-blue.svg)](https://www.spaceappschallenge.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

---

## 🎯 About the Challenge

Planetary seismology missions face a critical constraint: the enormous power requirements needed to transmit continuous seismic data across millions of kilometers back to Earth. However, only a small fraction of this data contains scientifically valuable information.

**The Challenge:** Instead of transmitting all collected data, can we develop intelligent systems that enable landers to autonomously distinguish meaningful seismic signals from background noise?

Our mission was to create a computer program capable of analyzing real data from historic Apollo missions and the Mars InSight Lander to accurately identify seismic events within noisy datasets—enabling smarter, more efficient planetary exploration.

---

## 👥 Team Members

| Name | Institution | Program |
|------|-------------|---------|
| **Alejandro Repetto** | UTN, Rosario, Argentina | Ingeniería en Sistemas |
| **Alejo Lo Menzo** | UNR, Rosario, Argentina | Tecnicatura en Inteligencia Artificial |
| **Luca Braccani** | UTN, Rosario, Argentina | Ingeniería en Sistemas |
| **Matías Taborda** | UNR, Rosario, Argentina | Tecnicatura en Inteligencia Artificial |
| **Miguel Mussi** | UNR, Rosario, Argentina | Tecnicatura en Inteligencia Artificial |
| **Ramiro Sagrera** | UNR, Rosario, Argentina | Tecnicatura en Inteligencia Artificial |

---

## 🚀 Project Overview

We developed an **LSTM-based neural network model** to detect seismic events in data collected by seismometers deployed on the Moon and Mars. Our solution addresses a fundamental challenge in planetary science: the difficulty of transmitting massive volumes of data from distant celestial bodies when only a fraction contains useful seismic signals.

### Key Innovation

Our approach processes seismic data **directly on the lander**, enabling real-time differentiation between genuine seismic signals and environmental noise. This allows missions to transmit only scientifically relevant measurements back to Earth.

### Why This Matters

- **Energy Optimization:** Dramatically reduces power consumption by minimizing data transmission requirements
- **Scientific Efficiency:** Maximizes the scientific return of space missions by focusing on meaningful data
- **Real-Time Analysis:** Enables autonomous seismic event detection without waiting for Earth-based processing
- **Mission Longevity:** Conserves limited resources, extending operational lifespans of planetary landers

### Scientific Impact

By automatically identifying seismic events in real-time, we significantly reduce unnecessary data transmission while enabling deeper exploration of the seismic characteristics of Mars and the Moon. These studies are essential for:

- Understanding internal planetary structures
- Mapping tectonic processes and geological evolution
- Gaining insights into rocky planet formation across the solar system
- Advancing our knowledge of planetary differentiation and core composition

---

## 🛠️ Technical Approach

Our solution leverages **Long Short-Term Memory (LSTM)** neural networks, which excel at detecting patterns in time-series data—making them ideal for identifying seismic signatures within noisy sensor readings from extreme environments.

### Model Architecture
- **Input:** Raw seismometer time-series data from Apollo and InSight missions
- **Processing:** Multi-layer LSTM network trained to recognize seismic event patterns
- **Output:** Binary classification (seismic event detected / noise)

### Training Data
- Apollo mission lunar seismic data
- Mars InSight Lander seismometer readings
- Labeled datasets with confirmed seismic events and noise periods

---

## 📊 Results & Performance

*[Add your model's performance metrics, accuracy, precision, recall, etc.]*

---

## 🔗 Resources

- [NASA Space Apps Challenge](https://www.spaceappschallenge.org/)
- [Apollo Seismic Data](https://www.spaceappschallenge.org/nasa-space-apps-2024/challenges/seismic-detection-across-the-solar-system/)
- [Mars InSight Mission](https://mars.nasa.gov/insight/)

---

## 📝 License

*[Add your license information]*

---

## 🙏 Acknowledgments

We thank NASA and the Space Apps Challenge organizers for providing this opportunity to contribute to planetary science research, and for making historic Apollo and InSight mission data accessible to researchers and developers worldwide.

---

<div align="center">
  <strong>🌙 From the Moon to Mars and beyond 🔴</strong>
</div>
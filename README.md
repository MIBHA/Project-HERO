# Project HERO (Heuristic Emergency Response Optimizer)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-380/)

## 📖 Description
* An **AI-powered optimization system** designed to minimize emergency response times in complex urban environments.
* Uses **Multi-Agent Reinforcement Learning (MARL)** to train a fleet of emergency vehicles for a cooperative dispatch strategy.
* Operates within a **high-fidelity traffic simulation** built with [SUMO](https://www.eclipse.org/sumo/) and real-world map data from [OpenStreetMap](https://www.openstreetmap.org/).

## 🎯 Introduction

### Background
In densely populated cities, **every second counts** during an emergency. Traditional dispatch systems often use a simple "closest-unit" logic, which is suboptimal as it fails to account for dynamic variables like **real-time traffic** and the likelihood of future incidents.

### Motivation
This project is driven by the potential of modern AI to solve **complex, real-world logistical challenges** with a significant social impact. We aim to apply advanced **Multi-Agent Reinforcement Learning (MARL)** techniques to create a smarter, faster, and more efficient emergency response network.

## ✨ Features
* **Dynamic Traffic Simulation:** Simulates realistic, unpredictable traffic patterns using the **SUMO engine**.
* **Predictive Hotspot Modeling:** Identifies areas with a high probability of future incidents for **proactive positioning**.
* **Cooperative AI Agents:** Employs MARL to teach independent agents a **coordinated dispatch strategy**.

## 🛠️ Tech Stack
* **Simulation:** SUMO
* **Core Language:** Python
* **AI/ML Libraries:** Ray RLlib, Scikit-learn, Pandas
* **Simulation Bridge:** Traci

## 🚀 Getting Started

### Prerequisites
* [Python 3.8+](https://www.python.org/downloads/release/python-380/)
* [SUMO](https://sumo.dlr.de/docs/Installing.html) (Installed and added to PATH)

### Installation & Usage
1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/Project-HERO.git](https://github.com/YourUsername/Project-HERO.git)
    cd Project-HERO
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the main simulation script (coming in Phase 3):
    ```bash
    python src/run_simulation.py
    ```

## 📂 Project Structure
```
Project-HERO/
├── data/              # Incident prediction datasets
├── notebooks/         # Jupyter notebooks for analysis
├── simulation_files/  # SUMO map & config files
├── src/               # All Python source code
└── README.md
```

# Project HERO

**HERO (Heuristic Emergency Response Optimizer)** is an AI system designed to find the fastest routes for emergency vehicles in busy cities.

It uses a **multi-agent reinforcement learning (MARL)** approach to train a fleet of vehicles to cooperate and learn the best dispatch strategies. The system is built on a realistic traffic simulation using **SUMO** and **OpenStreetMap** data.

The goal is to replace simple "closest vehicle" dispatching with an intelligent system that understands real-time traffic, predicts incident hotspots, and ultimately **saves lives by reducing response times.**

## Tech Stack

* **Simulation**: `SUMO`
* **Core Language**: `Python`
* **AI/ML**: `Ray RLlib`, `Stable Baselines3`, `Scikit-learn`
* **Geospatial**: `OpenStreetMap`

## Getting Started

### Prerequisites

* Python 3.8+
* SUMO installed (see [SUMO Installation Guide](https://sumo.dlr.de/docs/Installing.html))

### Installation & Usage

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/YourUsername/Project-HERO.git](https://github.com/YourUsername/Project-HERO.git)
    cd Project-HERO
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run a simulation:**
    ```bash
    python src/run_simulation.py
    ```

# Three-Body Problem Simulation & Chaos Analysis

## Overview
This repository presents a numerical analysis of chaos and stability within the gravitational Three-Body Problem. The project implements an 8th-order Runge-Kutta (RK8) method and utilizes Lyapunov exponents to quantify chaotic behavior across various configurations, including the Solar System, Figure-8, and Burrau's scenarios.

![Figure-8 Simulation](gifs/figure8_drift.gif)

## Highlights
* **Numerical Integration:** Modeling of three-body gravitational dynamics using an 8th-order Runge-Kutta method (DOP853).
* **Chaos Analysis:** Implementation of Lyapunov exponent calculations to measure the system's sensitivity to initial conditions.
* **3D Visualization:** Generation of 3D orbital trajectories utilizing Matplotlib.

## Technologies Used
* **Language:** Python 3.13+
* **Numerical Modeling:** NumPy, SciPy
* **Visualization:** Matplotlib

## Getting Started

This project uses `uv` for Python environment management. 

### Installation & Usage

1. **Clone the repository:**
   `git clone https://github.com/m-kuchta/three-body-simulation.git`
   `cd three-body-problem`

2. **Sync the environment (this automatically creates a .venv and installs dependencies):**
   `uv sync`

3. **Activate the virtual environment:**
   * Linux/macOS: `source .venv/bin/activate`
   * Windows: `.venv\Scripts\activate`

4. **Run the simulation:**
   Launch Jupyter and open the simulation notebook:
   `jupyter notebook three_body_problem.ipynb`

# Three-Body-Problem
Numerical analysis of chaos and stability in the gravitational Three-Body Problem. Implementation of 8th-order Runge-Kutta method and Lyapunov exponents for Solar System, Figure-8, and Burrau's scenarios. 

![Figure-8 Simulation](gifs/figure8_drift.gif)

## 🌌 Project Overview
This project investigates the complex dynamics of the Three-Body Problem, a classic challenge in celestial mechanics where three bodies interact through Newtonian gravity. The study focuses on identifying deterministic chaos and assessing stability across different initial configurations.

## 🚀 Key Features
* **High-Order Numerical Integration:** Implementation of the **8th-order Runge-Kutta method** to solve a system of 18 first-order differential equations.
* **Chaos Quantification:** Calculation of **Lyapunov exponents** ($\lambda$) to measure the sensitivity to initial conditions.
* **Unit Normalization:** Use of canonical units (Solar mass, AU) to minimize numerical errors.

## 🧪 Analyzed Scenarios
The simulator evaluates three distinct gravitational setups:
1. **Sun-Earth-Mars:** A simplified planetary model demonstrating regular, periodic orbits with high stability.
2. **Figure-8 Orbit:** A unique periodic solution where three equal masses follow a single figure-eight track.
3. **Pythagoras (Burrau's Problem):** A highly chaotic scenario starting with three bodies at the vertices of a 3-4-5 triangle, leading to extreme sensitivity and the eventual ejection of one body.

## 📊 Methodology & Findings
* **Stability Analysis:** Tested system sensitivity by introducing minor perturbations ($\epsilon = 10^{-12}$ AU).
* **Dimensional Resilience:** Observed that while X/Y perturbations in planar systems often lead to chaos, Z-axis perturbations (inclination changes) maintain geometric stability.
* **Maximum Chaos:** Burrau's Problem exhibited the highest Lyapunov exponents, confirming it as the most chaotic scenario tested.


<div align="center">

<img src="assets/EntropyCollapseSim_Logo.png" width="180"/>

# EntropyCollapseSim: Collapse Bias Explorer

![License](https://img.shields.io/badge/license-Provisional%20Patent-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-green)
![Platform](https://img.shields.io/badge/Quantum-PennyLane%20%7C%20Qiskit-purple)
![Status](https://img.shields.io/badge/status-Prototype%20Ready-yellow)

**Explore collapse behavior beyond the Born rule. Visualize quantum entropy in action.**

</div>

---

## 🔬 What Is EntropyCollapseSim?

**EntropyCollapseSim** is an entropy-aware simulator that compares quantum measurement outcomes in **clean** vs **entropy-injected** circuits based on the **PDQC (Probability-Driven Quantum Collapse)** theory.

It enables direct visualization and quantification of collapse bias using:
- 🧼 Standard Born-rule behavior
- 🌪 Entropy-modulated collapse (e.g. injected via RY and RZ gates)

---

## 🧠 Features

- ✅ Supports Bell, GHZ, QFT, and custom circuits
- 🔁 Simulates both clean and entropy-biased quantum collapse
- 📊 Outputs histograms, entropy traces, and collapse bias metrics
- 📐 Calculates:
  - **KL Divergence**
  - **Jensen-Shannon Divergence**
  - **QWI-PI² Collapse Bias Score**
- 📈 Includes visuals and ready-to-run notebooks

---

## 📊 QWI-PI² Collapse Bias Score

> **QWI-PI²** (*Quantum Weighted Information – Probabilistic Irregularity Index*)  
This custom metric detects entropy-driven irregularities in the collapse distribution. It emphasizes:
- Entropic variance across bitstrings
- Divergence from uniformity or expected Born-rule collapse
- Temporal and spatial entropy weighting

A **higher QWI-PI² score** indicates stronger collapse distortion — a signature of entropy-aware measurement effects.

---

## ⚙️ Installation

Install required packages:

```bash
pip install pennylane qiskit matplotlib seaborn numpy scipy

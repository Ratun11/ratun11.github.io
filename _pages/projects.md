---
title: "Projects"
permalink: /projects/
author_profile: true
---

This page presents selected software frameworks and experimental platforms
that I have developed for quantum computing, quantum machine learning,
quantum sensing, and distributed quantum learning.

## QuSenseSim

**Interactive Quantum Sensing Simulation Framework — 2026**

QuSenseSim is a modular and interactive simulation framework for studying
multi-sensor quantum sensing systems under realistic and heterogeneous noise
conditions.

The framework integrates parameterized quantum circuits, adaptive noise
injection, and personalized mitigation strategies. It enables real-time
evaluation using Fisher Information and the Cramér–Rao Bound.

Key features include:

- Multiple configurable quantum sensors
- Heterogeneous sensor noise
- Adaptive error-mitigation strategies
- Fisher Information analysis
- Cramér–Rao Bound evaluation
- Interactive visualization
- User-controlled collaboration settings

[View QuSenseSim on GitHub](https://github.com/Ratun11/QuSenseSim){: target="_blank" }

---

## QuNoise

**Quantum Noise Simulator and Visual Analytics Platform — 2026**

QuNoise is a simulation and visualization platform for analyzing the effects
of realistic quantum noise on quantum circuits and quantum learning systems.

The platform supports several noise channels and mitigation methods, enabling
users to examine model robustness, output stability, and mitigation
performance under different NISQ conditions.

Supported noise models include:

- Depolarizing noise
- Amplitude damping
- Phase damping
- Readout errors

Supported mitigation techniques include:

- Zero-noise extrapolation
- Probabilistic error cancellation
- Measurement error mitigation

[View QuNoise on GitHub](https://github.com/Ratun11/QuNoise){: target="_blank" }

---

## SimQFL

**Distributed Quantum Federated Learning Simulator — 2025**

SimQFL is a scalable client-server simulation framework for studying quantum
federated learning under heterogeneous data, devices, and noise conditions.

The platform enables researchers to configure multiple quantum clients,
simulate client-specific quantum noise, perform federated aggregation, and
observe the behavior of distributed quantum learning systems.

Key features include:

- Configurable quantum clients
- Client-level data heterogeneity
- QPU-specific noise models
- Noise-aware quantum training
- Federated model aggregation
- Secure aggregation support
- Real-time training visualization
- Convergence and performance monitoring

[View SimQFL on GitHub](https://github.com/Ratun11/SimQFL){: target="_blank" }

---

## ZNE-Rigetti

**Real-Hardware Quantum Noise Mitigation on Rigetti QPU — 2026**

ZNE-Rigetti is a real-hardware quantum error-mitigation framework developed
using Amazon Braket and the Rigetti Cepheus-1-108Q superconducting quantum
processor.

The framework implements zero-noise extrapolation using multiple
circuit-folding scales and supports task-level tracking of quantum hardware
executions.

The real-device experiments include:

- Multiple zero-noise extrapolation arms
- Pauli-Z expectation-value estimation
- Circuit-folding scale comparison
- Accuracy and loss evaluation
- Entropy and reward analysis
- Runtime tracking
- Hardware-cost analysis
- CIFAR-10 quantum inference experiments

The project completed 240 real-QPU tasks, enabling practical evaluation of
quantum error mitigation under real NISQ execution constraints.

[View ZNE-Rigetti on GitHub](https://github.com/Ratun11/zne-rigetti-real-quantum-device){: target="_blank" }

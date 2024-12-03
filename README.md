#Integral Lattice-Based Cryptosystems: NTRU & LLL
## Visual Results

Here are some visual results and insights from our project:

| **Training Loss Curve with Fixed Threshold** | **Training Loss Curve with Scheduler** |
|-------------------------------|-------------------------------|
| ![Pseudo-Labels](plots/noScheduler.jpg) | ![Accuracy](plots/Scheduler_loss_10.png) |


| **Pseudo-Label Distribution** | **Threshold and Confidence with Scheduler** |
|-------------------------------|-------------------------------|
| ![Pseudo-Labels](plots/barchart.png) | ![Accuracy](plots/threshold_scheduling.png) |
## Overview
This repository contains the implementation and simulation of cryptographic concepts and attacks related to lattice-based systems, focusing on the NTRU cryptosystem and the Lenstra-Lenstra-Lovász (LLL) algorithm. It also includes simulations for the density of invertible elements in polynomial rings and an attack simulation on NTRU using LLL.

### Features
1. **NTRU Implementation**:
   - Encryption and decryption schemes based on the NTRU cryptographic system.
   - Parameter selection for security and efficiency trade-offs.
   - Simulation of the probability of invertible polynomials critical to NTRU's correctness.

2. **LLL Algorithm**:
   - Implementation of the LLL algorithm for lattice basis reduction.
   - Application of the LLL algorithm to identify vulnerabilities in NTRU.

3. **Simulations**:
   - Probability and density of invertible elements in polynomial rings.
   - Visualization of results through graphs.

4. **Attacks on NTRU**:
   - Lattice-based attacks demonstrating vulnerabilities in specific parameter choices.

---

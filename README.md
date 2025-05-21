# Reimplementation and Evaluation of Hybrid Quantum Deep Learning and VQC Models for Botnet DGA Detection

**Authors:**  
Mohammad Alshurbaji – [malshur@clemson.edu](mailto:malshur@clemson.edu)  
Fateme Mazdarani – [fmazdar@clemson.edu](mailto:fmazdar@clemson.edu)  
School of Computing, Clemson University

---

## Overview

This project revisits and extends prior research on using **Quantum Machine Learning (QML)** for **Botnet Domain Generation Algorithm (DGA) detection**—a critical task in cybersecurity. It focuses on reimplementing and evaluating:

- A **Variational Quantum Classifier (VQC)** using the latest `Qiskit` framework
- A **Hybrid Quantum-Classical Deep Learning Model**

We explore the effectiveness and limitations of quantum-enhanced cybersecurity models by replicating experimental pipelines and evaluating modern quantum circuits and optimizers.

---

## Objectives

- Reproduce the **VQC** model for DGA detection and benchmark its performance
- Experiment with various **quantum feature maps**, **ansätze**, and **classical optimizers**
- Re-implement the **hybrid quantum deep learning model** (QNN + CNN)
- Analyze the **compatibility issues** caused by framework updates and software deprecations
- Discuss the **real-world viability** of quantum approaches in cybersecurity

---

## Technologies Used

- Python 3.10+
- [Qiskit](https://qiskit.org/) for quantum model development
- NumPy, Pandas, Scikit-learn for classical ML pipelines
- Matplotlib, Seaborn for visualization

---


---

## Results Summary

- **VQC models** achieved comparable results to traditional ML baselines on a preprocessed DGA dataset
- **Feature map and ansatz choice** significantly influenced VQC performance
- **Hybrid model reimplementation** was partially successful but blocked by framework deprecations and versioning issues
- Findings highlight both the **potential** and the **current limitations** of QML in real-world cybersecurity contexts

---

## Challenges

- Software version mismatches in Qiskit and TensorFlow Quantum hindered the hybrid model reimplementation
- Computational constraints limited full-scale experimentation on real quantum hardware
- Quantum models are **not yet production-ready** for high-stakes threat detection, but hold promise for future exploration

---

## Conclusion

This project affirms the **promise of quantum machine learning** in cybersecurity while revealing practical barriers that researchers must overcome. The VQC model shows meaningful potential, but further progress in hardware, frameworks, and reproducibility is needed before quantum methods can be reliably deployed for real-world botnet detection.

---

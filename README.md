# Quantum Anomaly Detection with Quantum Density Estimation

#### Here we present our project for the Qiskit Hackathon Global 2021

---

### **Our Group:**

#### **Quantum Mind UN**

Diego Useche - diusecher@unal.edu.co

Oscar Alberto Bustos B. - oabustosb@unal.edu.co

### **The problem:**

Anomaly Detection: 
A common need when analyzing datasets is to find which observations deviates considerably from others. Such instances are known as anomalies or outliers, and the goal of anomaly detection (AD) is to detect those atypical or irregular data, generally in unsupervised scenarios. AD has many applications across a wide variety of domains, including intrusion or fraud detection in cybersecurity, industrial monitoring, disease detection for medical diagnosis and rare event detection in science.

*Can we build a quantum circuit to perform Anomaly Detection?*

### **Our Approach:**

Anomaly Detection based on Density Estimation:

*   Use normal data to induce a probability density function (pdf) (Density Estimation)
*   Use the pdf to estimate the density of new samples. If the density is below a threshold, then classify it as anomaly.

Quantum Density Estimation:

*   Combine Density Matrices with Random Fourier Features to perform Density Estimation.
*   Propose a quantum circuit to estimate expected values of density matrices.

### **Main contributions:**

*   We developed a new method for Anomaly Detection in quantum computers.
*   We implemented the method in a quantum circuit and showed that it’s a feasible approach.
*   Most quantum machine learning algorithms are based on pure states. Our 
algorithm can work with mixed states and pure states.
*   We develop a new method to calculate the expected value of a density matrix.
*  We used this method to approximate a probability density function (pdf) in a quantum computer.

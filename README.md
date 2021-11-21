# Anomaly Detection & Density Estimation with Density Matrices

#### Here we present our project for the Qiskit Hackathon Global 2021

---

### **Our Group:**

#### **Quantum Mind UN**

Diego Useche - diusecher@unal.edu.co

Oscar Alberto Bustos B. - oabustosb@unal.edu.co

### **The problem:**

Anomaly Detection: 

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

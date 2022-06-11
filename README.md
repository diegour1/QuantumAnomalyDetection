# Computing expectation values of adaptive Fourier density matrices for quantum anomaly detection in NISQ devices

![](https://github.com/diegour1/QuantumAnomalyDetection/blob/main/Paper%20Experiments/QAD_Model.png)

Implementation of the preprint

- D. H. Useche, O. A. Bustos-Brinez, J. A. Gallego, and F. A. González, “Computing expectation values of adaptive Fourier density matrices for quantum anomaly detection in NISQ devices,” 1 2022. Available: https://arxiv.org/abs/2201.10006v2

## Abstract 

This article presents a novel classical-quantum anomaly detection model based on the expected values of density matrices and a new data embedding called adaptive Fourier features. The method works by estimating a probability density function of training data and classifying new samples as anomalies if they lie below a certain probability density threshold. As a core subroutine, we present a new method to estimate the expected value of a density matrix based on its spectral decomposition on a quantum computer. The anomaly detection model is tested with pure and mixed states and both adaptive and random Fourier features on a synthetic data set for density estimation and on a widely used data set for anomaly detection; results show the superior performance of adaptive Fourier features for density estimation and anomaly detection, and of mixed states for density estimation. An important finding of this work is to show that it is possible to perform anomaly detection with high performance on noise intermediate-scale quantum computers. 

## Dataset

The modified Cardiotography data set can be downloaded from the following link:

- http://odds.cs.stonybrook.edu/cardiotocogrpahy-dataset/

---

#### Here we present our project for the Qiskit Hackathon Global 2021

Part of this preprint was presented in the Qiskit Hackathon Global 2021

### **Our Group:**

#### **Quantum Mind UN**

Diego Useche - diusecher@unal.edu.co

Oscar Alberto Bustos B. - oabustosb@unal.edu.co

### **The problem:**

Anomaly Detection: 

For Qiskit Fall Fest Hackathon 2021, we proposed a quantum protocol to compute the expected value of any nxn density matrix. In this project, we improve this quantum circuit to develop a new method for anomaly detection. The method works by estimating the probability density function (pdf) of normal data and classifying as anomalies new data which lies below a probability threshold in the pdf.

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

# Linear-Logistic-Regression

This project implements linear and logistic regression models from scratch. We experimented with gradient descent techniques and analyzed their performance on two benchmark datasets: the **Infrared Thermography Temperature dataset** (regression task) and the **CDC Diabetes Health Indicators dataset** (classification task).

## Overview
- **Linear Regression**: Predict oral temperature using thermal imaging features.
- **Logistic Regression**: Classify diabetes status based on demographic and health indicators.

## Datasets
1. **Infrared Thermography Dataset**  [Here](https://archive.ics.uci.edu/dataset/925/infrared+thermography+temperature+dataset)  
   Goal: Predict average oral temperature using 33 features.
   
2. **CDC Diabetes Health Indicators Dataset**  [Here](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators)  
   Goal: Classify individuals' diabetes status based on lifestyle and healthcare indicators.

## Key Features
- **Implemented Models**:
  - Linear regression with analytical solution and gradient descent.
  - Logistic regression with mini-batch stochastic gradient descent (SGD).
  - Momentum added to gradient descent to accelerate convergence.

- **Experiments**:
  - Effect of **batch size** and **learning rate** on model performance.
  - Comparison of **mini-batch SGD** vs **analytical solution**.
  - Exploration of **model convergence** and handling **imbalanced data**.

## Results
- **Linear Regression** achieved an average R² score of 0.76 on training data.
- **Logistic Regression** showed better performance with smaller batch sizes, highlighting the noise-benefit in gradient descent.
- Adding **momentum** helped accelerate convergence but slightly reduced accuracy.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Misohhhh/COMP551-Assignment1.git
   cd COMP551-Assignment1

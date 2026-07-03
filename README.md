# Predictive Maintenance using Machine Learning

## Overview

This project implements a **Supervised Machine Learning (Binary Classification)** model to predict machine failures based on operational and sensor data.

The objective is to identify whether a machine is likely to fail by analyzing various factors such as machine lifetime, pressure, moisture, temperature, maintenance team, and provider information.

---

## Dataset Information

The dataset contains **1000 records** and **7 columns**.

### Features

| Feature | Description |
|----------|-------------|
| lifetime | Machine operating lifetime |
| pressureInd | Pressure indicator value |
| moistureInd | Moisture indicator value |
| temperatureInd | Temperature indicator value |
| team | Maintenance team responsible |
| provider | Equipment provider |
| broken | Target variable |

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | Machine Working |
| 1 | Machine Failed |

---

## Machine Learning Type

- Supervised Learning
- Binary Classification
- Predictive Maintenance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Encoding Categorical Features
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Prediction

---

## Project Goal

The goal of this project is to develop a machine learning model capable of predicting machine failures before they occur. Such predictive maintenance systems help reduce downtime, improve efficiency, and lower maintenance costs.

Mewar University

---

## License

This project is licensed under the MIT License.

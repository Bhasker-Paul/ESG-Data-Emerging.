# ESG-Data-Emerging.
Analysis of the impact of COVID-19 on bank risk using ESG, financial, and governance indicators with artificail neural networking–based feature importance.
This repository contains a machine learning project analyzing the impact of COVID-19 on bank risk using financial, ESG (Environmental, Social, Governance), and governance indicators.

The project demonstrates building and training an Artificial Neural Network (ANN), evaluating its performance, and analyzing feature importance to understand which factors most influence bank risk during the pandemic.


Project Overview

The objective of this project is to predict bank risk based on ESG and financial indicators during the COVID-19 period. Key components of the project include:

Data preprocessing and feature scaling using StandardScaler

Training and validation of an Artificial Neural Network (ANN)

Evaluation using accuracy, R², MAE, and MSE metrics

Feature importance analysis with Random Forest Regressor

Visualization of training and validation accuracy over epochs

Insights on ESG, financial, and governance factors impacting bank risk

This project is useful for financial analysts, data scientists, and researchers interested in risk modeling and ESG analytics.

Dataset Type: Tabular data with financial, ESG, and governance indicators

Task: Regression (predict bank risk)

Target Variable: Bank risk score

File Format: CSV (example: bank_risk_dataset.csv)

Data Split: Training and testing sets (typical 80:20 split)

Python

Pandas & NumPy

Matplotlib & Seaborn (visualization)

Scikit-Learn (preprocessing, Random Forest)

Statsmodels (statistical analysis)

TensorFlow & Keras (ANN modeling)

Google Colab

Neural Network Model

ANN architecture with input layer, hidden layers, and output layer

Activation function: ReLU (hidden layers), Sigmoid/Linear (output) depending on regression or classification

Loss function: MSE (regression)

Optimizer: Adam

Training monitored with accuracy/loss curves

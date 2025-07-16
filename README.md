# Intern Project: Predicting the Temperature of a Permanent Magnet in PMSMs

## Overview
This project focuses on predicting the temperature of the Permanent Magnet (PM) in Permanent Magnet Synchronous Motors (PMSMs). Prolonged operation of PMSMs can lead to overheating of the rotor’s PM, causing irreversible demagnetization—a major failure in electric motor systems. The goal is to build a reliable temperature forecasting model that can help prevent thermal damage by early prediction and alerting mechanisms.

## Problem Statement
Overheating in PMSMs affects long-term motor reliability and efficiency. In particular:
The permanent magnets in the rotor are vulnerable to irreversible thermal demagnetization.
Monitoring and forecasting the PM temperature is crucial to initiate protective actions before reaching critical thresholds.

## Dataset
Source: measures_v2.csv

Features Include:
Electrical variables (e.g., current, voltage)
Thermal readings from various parts of the motor (e.g., stator_yoke, stator_winding, etc.)
Environmental and operational parameters
Target Variable: pm — temperature of the permanent magnet (°C)

## Project Workflow

Data Loading & Initial Exploration
Importing and examining shape, types, and sample rows of the dataset.
Checking for missing values and outliers.
Data Preprocessing
Feature selection
Normalization / Standardization
Train-test split
Exploratory Data Analysis (EDA)
Correlation analysis
Distribution plots of thermal and electrical features
Time-series trends

## Model Development

Implemented using Neural Networks (ANN or LSTM depending on final architecture)
Training with respect to temporal dependencies
Validation and tuning for performance

## Evaluation Metrics
MSE, RMSE, MAE

## Visual plots:
true vs predicted values

## Conclusion & Future Work

Discussion on model accuracy and areas for improvement
Recommendations for real-world deployment in motor monitoring systems

## Tech Stack

Languages & Libraries: Python, NumPy, Pandas, Matplotlib, Seaborn
ML Frameworks: TensorFlow / Keras (if applicable in full notebook)
Jupyter Notebook for interactive development


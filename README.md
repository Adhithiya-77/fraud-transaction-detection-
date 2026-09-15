# 💳 Fraud Transaction Detection using Deep Learning

A Deep Learning-based web application that detects potentially fraudulent credit card transactions using a trained neural network model.

The project uses transaction data, preprocessing techniques, and a Keras/TensorFlow deep learning model to classify transactions as **legitimate or fraudulent**.

---

## 📌 Project Overview

Credit card fraud is a major problem in the financial industry. Traditional rule-based systems may struggle to identify complex and evolving fraud patterns.

This project uses **Deep Learning** to learn patterns from historical transaction data and predict whether a new transaction is:

- ✅ Legitimate Transaction
- 🚨 Fraudulent Transaction

The trained model is integrated into a **Flask web application**, allowing users to enter transaction details and receive a fraud prediction.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions using Deep Learning.
- Preprocess and normalize transaction features.
- Train a neural network using historical transaction data.
- Evaluate the performance of the trained model.
- Deploy the trained model through a Flask web application.
- Provide a simple interface for real-time fraud prediction.

---

## 🧠 Machine Learning / Deep Learning Approach

The project follows the following pipeline:

```text
Transaction Dataset
        ↓
Data Cleaning
        ↓
Data Preprocessing
        ↓
Feature Scaling
        ↓
Train / Test Split
        ↓
Deep Learning Model
        ↓
Model Evaluation
        ↓
Save Trained Model
        ↓
Flask Web Application
        ↓
Fraud Prediction

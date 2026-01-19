# Federated Learning for Heart Disease Prediction

This repository contains my course project for **Sustainable Artificial Intelligence in Healthcare**, where I developed a machine learning pipeline to predict heart disease severity and compared centralized vs federated learning approaches.

## 🧠 Project Overview

The project uses the **UCI Heart Disease dataset** and applies:

- Data preprocessing & feature engineering
- Multiclass classification of disease severity
- Logistic Regression, Random Forest, and XGBoost models
- Model interpretability with SHAP values
- Federated Learning to enable privacy-preserving model training across multiple hospitals

## 📂 Repository Structure

- `data/heart_disease_uci.csv` — Dataset used for modeling
- `notebooks/main.ipynb` — Full ML workflow and experiments
- `reports/Federated Learning for Heart Disease Prediction.pdf` — Final project report and results
- `Killchain.png`, `Diamond Model.png` — Supporting visuals

## ⚙️ Models Implemented

| Model | Accuracy | F1 Score |
|-------|---------|---------|
| Logistic Regression | 0.59 | 0.58 |
| Random Forest | 0.62 | 0.60 |
| XGBoost | 0.64 | 0.62 |

Federated learning was also tested, showing slightly lower performance than centralized training, but offering a more ethical and privacy-aware deployment strategy.

## 🎯 Purpose

This project demonstrates how **ethical and sustainable AI** can be applied to real-world healthcare prediction problems while protecting patient privacy through federated learning.

---

Created as part of my MSc in Artificial Intelligence at Kristiania University College, Oslo.

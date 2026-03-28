# Cost_Sensitive-Fraud-Detection-Handling-Extreme-Class-Imbalance-And-Threshold-Tuning
# Precision Fraud Shield: Cost-Sensitive ML for Financial Security
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) ![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)

## 📌 Business Problem
Credit card fraud costs financial institutions billions annually. The technical challenge lies in the **extreme class imbalance**: only **0.17%** of transactions are fraudulent. A standard model might achieve 99% accuracy by simply predicting "Not Fraud" for every case, but it would fail to save a single dollar in losses.

## 🚀 The Solution
This project implements a cost-sensitive machine learning pipeline that prioritizes **Recall** (catching fraud) while minimizing **False Positives** (customer friction).

### Key Features:
* **Advanced Resampling:** Utilized **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the training set without losing critical information.
* **Algorithmic Comparison:** Benchmarked **Decision Trees** against **Linear SVM** to find the optimal balance between interpretability and high-dimensional separation.
* **Custom Threshold Tuning:** Moved beyond the default 0.5 probability threshold to find the "Economic Sweet Spot" that minimizes total business cost.

## 🛠️ Tech Stack
Python | Pandas | Scikit-learn | Imbalanced-learn (SMOTE) | Matplotlib | Seaborn

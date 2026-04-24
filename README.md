### Credit Card Fraud Detection System
This project demonstrates your ability to handle real-world data challenges like extreme class imbalance and outlier scaling.

```
# 💳 Credit Card Fraud Detection System

An end-to-end Machine Learning pipeline to identify fraudulent transactions in highly imbalanced datasets.

## 🧠 Methodology
This system addresses the challenge of "needle-in-a-haystack" detection using a hybrid approach:
- **Resampling**: Uses **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the training data.
- **Scaling**: Implements **Robust Scaling** to handle outliers in transaction time and amount.
- **Modeling**: Features an **XGBoost** classifier for high-precision supervised learning.



## 📊 Features
- **Real-time Prediction**: Sidebar sliders to input transaction features (V1-V28).
- **Probability Scoring**: Returns the likelihood of fraud for every check.
- **Robust Preprocessing**: Built-in data loader with a dummy data generator for demonstration.

## 🛠️ Tech Stack
- **ML Frameworks**: Scikit-learn, XGBoost, Imbalanced-learn
- **Data Handling**: Pandas, Numpy
- **Deployment**: Streamli

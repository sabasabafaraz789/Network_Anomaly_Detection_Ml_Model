# [Network Anomaly Detection with ML](

This project focuses on detecting anomalies and malicious activities in network traffic using Machine Learning techniques. By analyzing network flow features such as protocol, service type, packet statistics, and traffic behavior, the model can classify network traffic as normal or attack-related.

## Dataset Sources

Network traffic data 59410 samples from  [UNSW_NB15](https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15)

## Key Technical Components

**1. Data Preprocessing**
Handled missing and inconsistent values

Converted boolean values to numerical format

Applied encoding techniques for categorical features:

Target Encoding to 'Proto' column

One-Hot Encoding to Other Categorical Columns

Applied scaling/normalization for numerical stability

**2. Machine Learning Models**

The project implements and compares multiple ensemble models:

Logistic Regression

Random Forest

Gradient Boosting

XGBoost

Gradient Boosting

**3. Model Evaluation**

Evaluated model performance using:

Accuracy

Confusion Matrix

Classification Report

Verified correct handling of unseen or missing features


## Performance Results

**Best Model:** Random Forest

**Accuracy:**  1.0

**ROC-AUC:** 1.0

**Random Forest - Confusion Matrix:**
[[10262     0]
 [    0  7561]]


## 👨‍💻 Author
Developed by **Saba Faraz**  
📧 Email: farazsaba96@gmail.com

---

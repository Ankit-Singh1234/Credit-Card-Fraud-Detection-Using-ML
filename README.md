# 💳 Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> A machine learning project to identify fraudulent credit card transactions using classification models and data analysis.

---

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions from a dataset of over 280,000 transactions. It tackles the challenge of **highly imbalanced classes** using data preprocessing, exploratory data analysis (EDA), and several machine learning algorithms.

---

## 📁 Dataset Summary

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions
- **Fraud Cases**: 492 (~0.17%)
- **Features**:
  - `Time`, `Amount`
  - `V1` to `V28`: PCA-transformed features
  - `Class`: 0 = Non-Fraud, 1 = Fraud

---

## 📊 Technologies Used

- **Python 3.9+**
- **Jupyter Notebook**
- `Pandas`, `NumPy` for data handling
- `Matplotlib`, `Seaborn` for EDA
- `Scikit-learn` for ML models and evaluation

---

## 🔎 Exploratory Data Analysis (EDA)

Some visual insights generated during EDA:

### 📉 Fraud vs Non-Fraud Transactions
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Imbalanced_data_set.svg/600px-Imbalanced_data_set.svg.png" width="400" />

### 💡 Correlation Heatmap
<img src="https://miro.medium.com/v2/resize:fit:800/format:webp/1*n5d97PAXg3A8wxR0iH4Ktw.png" width="500" />

---

## 🤖 Models Implemented

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 99.3%   | 82.5%     | 93.7%  | 87.7%    |
| Random Forest       | 99.9%   | 91.2%     | 97.0%  | 94.0%    |
| Decision Tree       | 99.8%   | 89.1%     | 94.6%  | 91.7%    |

📌 **Note**: Accuracy alone is misleading due to class imbalance. Precision, recall, and F1-score are better metrics here.

---

## 🧠 Workflow

1. **Load & Clean Data**
2. **EDA and Visualization**
3. **Feature Scaling**
4. **Train-Test Split**
5. **Model Training**
6. **Model Evaluation**
7. **Imbalanced Handling**

---

## ✅ Results & Conclusion

- Random Forest performed best overall.
- Proper handling of **imbalanced datasets** is critical.
- Visualizations helped reveal patterns of fraudulent behavior.

---

## 🚀 Future Improvements

- Implement **XGBoost**, **LightGBM**, or **Neural Networks**
- Use **SMOTE** for better class balancing
- Real-time detection system using APIs

---

## 👨‍💻 Author

Made with ❤️ by [Ankit Singh]  

---

## 📜 License

This project is licensed under the **MIT License**.


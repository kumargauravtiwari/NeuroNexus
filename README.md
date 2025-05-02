# NeuroNexus

# 🛡️ Credit Card Fraud Detection Using Machine Learning

Detect fraudulent credit card transactions using machine learning models like Logistic Regression and Random Forest, while handling class imbalance with SMOTE and evaluating performance using classification metrics and visualizations.

---

## 📁 Project Overview

This project uses a real-world dataset of credit card transactions to build a binary classification model that identifies fraudulent transactions. The dataset is highly imbalanced, with only a small percentage of fraud cases, so special care is taken to address this issue using oversampling techniques.

---

## 🚀 Features

* Data preprocessing and normalization
* Exploratory data analysis with visualizations
* Handling class imbalance using **SMOTE**
* Training two classifiers: **Logistic Regression** and **Random Forest**
* Evaluation using:

  * Precision, Recall, F1-score
  * Confusion matrix heatmaps
* Visualization of class distribution and correlation matrix

---

## 🧠 Algorithms Used

* **Logistic Regression**: A simple yet effective linear model for binary classification.
* **Random Forest**: A robust ensemble method using multiple decision trees for improved accuracy and robustness.

---

## 🗂️ Dataset

* **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* Contains transactions made by European cardholders in September 2013.
* Features:

  * `Time`, `Amount`, and 28 anonymized features (V1–V28)
  * `Class` (target): 0 = Genuine, 1 = Fraudulent

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Visualizations
* **scikit-learn** – Machine learning models and preprocessing
* **imblearn (SMOTE)** – Handling class imbalance

---

## 📊 Visualizations

* Class distribution
* Correlation matrix
* Confusion matrix heatmaps

---

## 📈 Evaluation Metrics

| Metric           | Description                                       |
| ---------------- | ------------------------------------------------- |
| Precision        | % of predicted frauds that were actually fraud    |
| Recall           | % of actual frauds that were correctly identified |
| F1-score         | Harmonic mean of precision and recall             |
| Confusion Matrix | Summary of true/false positives and negatives     |

---

## 📦 How to Run This Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place `creditcard.csv` in the project folder.

4. Run the Jupyter Notebook or Python script:

   ```bash
   python fraud_detection.py
   ```

---

## ✅ Results

* Random Forest achieved higher precision and recall than Logistic Regression.
* Using SMOTE significantly improved detection of fraudulent transactions.
* Confusion matrix visualizations help understand model errors.

---

## 📌 Folder Structure

```
credit-card-fraud-detection/
│
├── fraud_detection.py          # Main Python script
├── creditcard.csv              # Dataset (not included for size reasons)
├── README.md                   # Project documentation
├── requirements.txt            # Python package requirements
```

---

## 📚 References

* [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* [Scikit-learn Documentation](https://scikit-learn.org/)
* [SMOTE - Imbalanced-learn](https://imbalanced-learn.org/)

---

## 🧑‍💻 Author

**Your Name**
[GitHub](https://github.com/kumargauravtiwari)

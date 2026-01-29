## 📌 Overview
Credit card fraud is a critical problem in the financial industry, leading to huge monetary losses every year.  
This project implements a **machine learning–based fraud detection system** using the **Light Gradient Boosting Machine (LightGBM)** algorithm to classify transactions as **fraudulent** or **legitimate**.

The model is designed to handle **highly imbalanced data** and focuses on minimizing **false negatives**, ensuring that fraudulent transactions are detected effectively.


## 📊 Dataset
- Contains credit card transaction data
- Highly imbalanced dataset
- Features are anonymized numerical values
- Target variable:
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction

> Dataset details are omitted for privacy and security reasons.

---

## ⚙️ Data Preprocessing
- Data cleaning and validation
- Train-test split
- Handling class imbalance using class weights
- Feature normalization (if required)

---

## 📈 Model Evaluation
The model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

> Recall is prioritized to reduce missed fraud cases.

---

## 🧪 Results
- LightGBM performed well on imbalanced data
- Achieved strong recall with low false negatives
- Outperformed baseline models

*(Results may vary depending on dataset and parameters.)*

---

## 🛠️ Technologies Used
- Python
- LightGBM
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection

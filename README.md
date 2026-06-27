# 💳 Credit Card Fraud Detection Using Machine Learning
Machine learning project for detecting fraudulent credit card transactions using Python and Scikit-learn.
 
## 📌 Project Overview

Credit card fraud is one of the biggest challenges faced by financial institutions. Fraudulent transactions result in significant financial losses and reduce customer trust. This project aims to build a Machine Learning model that can accurately classify credit card transactions as **Genuine** or **Fraudulent**.

The project uses a publicly available dataset containing anonymized credit card transactions and applies multiple machine learning algorithms to detect fraudulent activities.

---

## 🎯 Objectives

- Understand credit card fraud detection.
- Perform Exploratory Data Analysis (EDA).
- Handle an imbalanced dataset.
- Train multiple Machine Learning models.
- Compare model performance using appropriate evaluation metrics.
- Identify the best-performing model for fraud detection.

---

## 📂 Dataset

**Dataset:** Credit Card Fraud Detection Dataset

- Total Transactions: **284,807**
- Fraud Transactions: **492**
- Genuine Transactions: **284,315**

Features:
- Time
- V1 - V28 (Anonymized using PCA)
- Amount
- Class (Target Variable)

Target:
- **0 → Genuine Transaction**
- **1 → Fraudulent Transaction**

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Performance Comparison
10. Conclusion

---

## 🤖 Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Since the dataset is highly imbalanced, **Recall** and **F1-Score** are considered more important than Accuracy.

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── creditcard.csv
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Run all cells sequentially.

---

## 📌 Results

The trained machine learning models successfully classify credit card transactions into genuine and fraudulent categories. Performance is evaluated using multiple metrics, with special attention to minimizing false negatives due to the highly imbalanced nature of the dataset.

---

## 📚 Future Enhancements

- Apply SMOTE for class imbalance handling.
- Train advanced models such as XGBoost and Neural Networks.
- Deploy the model using Streamlit or Flask.
- Implement real-time fraud detection.
- Optimize hyperparameters for improved performance.

---

## 📜 License

This project is intended for educational and learning purposes.

---

## 👩‍💻 Author

**Naga Sunitha Kommuri**

Computer Science Engineering Student

Interested in Machine Learning, Data Science, and Artificial Intelligence.

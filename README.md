# Credit Card Fraud Detection Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Credit%20Card%20Fraud%20Detection-success)

**Author:** threo

## 📖 Abstract
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. This project proposes a robust machine-learning model to detect credit card fraud. The model is trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.

**Keywords:** Credit Card Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.

---

## 🚀 Overview

With the increase of people using credit cards in their daily lives, ensuring the security and safety of customers is critical. According to recent statistics, the number of credit card users worldwide continues to rise, and so do the reports of fraudulent behavior. There are generally two kinds of credit card fraud:
1. An identity thief opening a new account under your name.
2. An identity thief using an existing account by stealing card information.

These statistics motivated the analytical resolution of this issue by utilizing multiple machine learning methods to detect fraudulent credit card transactions among numerous legitimate ones.

---

## 🎯 Project Goals

The main aim of this project is the accurate detection of fraudulent credit card transactions to protect customers from unauthorized charges. 
- Build and evaluate multiple ML models (KNN, Logistic Regression, SVM, Decision Tree).
- Compare outcomes to identify the best and most suited model.
- Provide a comprehensive analysis with visualizations and performance metrics.
- Explore previous literature and techniques used to distinguish fraud within imbalanced datasets.

---

## 📂 Project Structure

```text
├── Code/                   # Jupyter notebooks containing model implementations
│   ├── Credit Card Fraud Detection - Decision Tree.ipynb
│   ├── Credit Card Fraud Detection - K-Nearest Neighbor.ipynb
│   ├── Credit Card Fraud Detection - Logistic Regression.ipynb
│   └── Credit Card Fraud Detection - Support Vector Machines.ipynb
├── Model/                  # Documentation related to the models
├── Presentation/           # Presentation slides for the project
├── Project Proposal/       # Initial project proposal documents
├── Report/                 # Final lab reports and latex files
└── README.md               # Project overview and instructions
```

---

## 📊 Data Source

The dataset was retrieved from Kaggle and contains transactions made in September 2013 by European cardholders. 
- **Timeframe:** 2 days
- **Size:** 284,808 rows and 31 attributes
- **Features:** 28 numerical attributes transformed using PCA (for confidentiality), plus `Time` and `Amount`.
- **Target Variable:** `Class` (0 = Legitimate Transaction, 1 = Fraudulent Transaction).

> **Dataset Link:** [Kaggle Dataset - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🛠️ Algorithms Used

The following algorithms were implemented and compared to find the most optimal solution:
1. **K-Nearest Neighbor (KNN)**
2. **Logistic Regression (L.R.)**
3. **Support Vector Machine (SVM)**
4. **Decision Tree (D.T.)**

---

## ⚙️ Setup and Installation

To run the Jupyter notebooks locally, you need Python installed along with some data science libraries.

1. **Clone the repository:**
   ```bash
   git clone <your-repository-url>
   cd CREDIT_CARD
   ```
2. **Install required libraries:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. Navigate to the `Code/` directory and open any of the notebooks to view the data analysis and model training steps.

---

## 🔮 Future Work

There are many ways to improve the model:
- **Diverse Datasets:** Testing the models on different datasets with varying sizes and data types.
- **Data Splitting & Sampling:** Exploring different data splitting ratios and advanced sampling techniques (like SMOTE) to handle class imbalance better.
- **Feature Engineering:** Integrating geographical data (e.g., telecom data) to calculate the cardholder's location during a transaction, adding a strong contextual layer for fraud detection.

---

## 🏆 Conclusion

The primary objective of this project was to determine the most suited model for credit card fraud detection. We successfully built and evaluated four different machine learning models. The models yielded excellent accuracy metrics, with **KNN** and **Decision Tree** showing the most promising results. Implementing such models can drastically improve credit card fraud detection rates, ultimately enhancing customer satisfaction and security.

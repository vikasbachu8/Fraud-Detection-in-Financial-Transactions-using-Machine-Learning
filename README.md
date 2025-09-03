# Fraud-Detection-in-Financial-Transactions-using-Machine-Learning
A fraud detection project that analyzes financial transactions using Python. Implements machine learning models (Logistic Regression &amp; Random Forest) to classify fraudulent vs legitimate activity.

This project builds a *fraud detection system* for financial transactions using *Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn*.
The goal is to classify whether a transaction is *fraudulent or legitimate*, based on patterns in the dataset.

### 🔎 Project Workflow

1. *Data Preprocessing & Cleaning*

   * Removed duplicates & handled missing values.
   * Extracted time-based features (hour, day).
   * Engineered new features (balance differences, zero-balance flags, merchant flag).
   * One-hot encoded transaction types.
   * Removed identifiers to prevent data leakage.

2. *Exploratory Data Analysis (EDA)*

   * Distribution of transactions (fraud vs non-fraud).
   * Correlation analysis of numeric features.

3. *Model Building*

   * Train-test split with stratification (to handle class imbalance).
   * Built ML pipelines with preprocessing + model training.
   * Models used:

     * *Logistic Regression* (baseline linear model)
     * *Random Forest Classifier* (ensemble learning).

4. *Model Evaluation*

   * Metrics: ROC-AUC, PR-AUC, classification report, confusion matrix.
   * Plots: ROC curve, Precision–Recall curve.
   * Compared performance of Logistic Regression and Random Forest.

### 🛠 Tech Stack

* *Python*
* *Pandas, NumPy* (data preprocessing)
* *Matplotlib, Seaborn* (visualization)
* *Scikit-learn* (ML models, pipelines, evaluation)

### 📊 Outcomes

* Built a fraud detection pipeline capable of identifying fraudulent transactions.
* Random Forest outperformed Logistic Regression in handling imbalanced fraud data.
* Demonstrated end-to-end ML workflow: data ingestion → feature engineering → model training → evaluation.

### 📂 Dataset

The dataset used in this project is publicly available on Kaggle.

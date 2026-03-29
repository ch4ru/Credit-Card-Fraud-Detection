

# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on **detecting fraudulent credit card transactions** using **machine learning techniques** applied to highly imbalanced financial transaction data.

The dataset consists of **anonymized numerical features (V1–V28)** generated via **PCA transformation**, along with transaction **time**, **amount**, and a **binary fraud label**.
The goal is to build a robust analytical workflow that can **identify fraud patterns while minimizing false positives**.

This notebook demonstrates core **data science competencies**, including:

* Exploratory Data Analysis (EDA)
* Handling imbalanced datasets
* Feature scaling and preprocessing
* Model training and evaluation
* Fraud detection performance metrics

---

## 🎯 Objectives

* Understand patterns in legitimate vs fraudulent transactions
* Handle severe class imbalance effectively
* Train and evaluate machine learning models for fraud detection
* Optimize recall and precision for minority (fraud) class
* Demonstrate an end-to-end data science workflow

---

## 🧰 Tech Stack

| Category         | Tools                          |
| ---------------- | ------------------------------ |
| Language         | Python                         |
| Data Analysis    | Pandas, NumPy                  |
| Visualization    | Matplotlib, Seaborn            |
| Machine Learning | Scikit-learn                   |
| Environment      | Jupyter Notebook               |
| Dataset Type     | Transactional / Financial Data |

---

## 📂 Project Structure

```bash
├── Credit_Card_Fraud_Detection.ipynb   # Main analysis & modeling notebook
├── README.md                          # Project documentation
```

---

## 📊 Dataset Description

The dataset represents **credit card transactions made by European cardholders**, where fraudulent activities are rare.

### Column Overview

| Column | Description                                                        |
| ------ | ------------------------------------------------------------------ |
| Time   | Seconds elapsed between each transaction and the first transaction |
| V1–V28 | Anonymized features obtained using PCA                             |
| Amount | Transaction amount                                                 |
| Class  | Target variable (0 = Legitimate, 1 = Fraud)                        |

> ⚠️ **Note:** Due to confidentiality, original features are not provided. PCA ensures privacy while retaining predictive patterns.

---

## ⚙️ Project Workflow

### 🔹 1. Data Loading & Inspection

* Read and inspect transaction data
* Validate data types and missing values
* Analyze transaction distributions

### 🔹 2. Exploratory Data Analysis (EDA)

* Fraud vs non-fraud class distribution
* Transaction amount comparison
* Time-based transaction behavior
* Correlation analysis across features

### 🔹 3. Data Preprocessing

* Feature scaling (Amount, Time)
* Train-test split with stratification
* Handling class imbalance using:

  * Undersampling / Oversampling
  * Class weighting techniques

### 🔹 4. Model Training

Models evaluated may include:

* Logistic Regression
* Decision Trees
* Random Forest
* Support Vector Machines

Focus placed on **fraud recall**, not just accuracy.

### 🔹 5. Model Evaluation

* Confusion Matrix
* Precision, Recall, F1-Score
* ROC-AUC Curve
* False Positive vs False Negative trade-offs

---

## 📈 Key Challenges Addressed

* **Extreme class imbalance** (fraud < 1%)
* Avoiding misleading accuracy metrics
* Optimizing business-critical KPIs (recall & precision)
* Preventing overfitting on minority class

---

## 🧠 Data Science Skills Demonstrated

* Imbalanced classification techniques
* Feature engineering & scaling
* Statistical reasoning
* Model comparison & validation
* Fraud detection domain understanding
* Clear analytical storytelling

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

### 2️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Launch the Notebook

```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

---

## 📌 Results & Insights

* Fraudulent transactions exhibit **distinct patterns** in feature space
* Accuracy alone is insufficient for fraud detection
* Models optimized for recall significantly improve fraud capture
* Proper preprocessing dramatically improves performance

---

## 🔮 Future Enhancements

* Implement SMOTE or advanced resampling methods
* Try ensemble and boosting algorithms (XGBoost, LightGBM)
* Add threshold tuning for business optimization
* Deploy model via API or Streamlit app
* Real-time fraud detection simulation

---


## 📄 License

This project is intended for **educational and portfolio use only**.
Dataset used strictly for research and demonstration purposes.



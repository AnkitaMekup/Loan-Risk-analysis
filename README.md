# 📊 Loan Risk Analytics Project

## 🔹 Overview

This project focuses on analyzing loan application data to identify high-risk customers and predict the likelihood of loan rejection. It simulates a real-world microfinance/credit risk scenario and demonstrates end-to-end data analytics and machine learning workflow.

---

## 🔹 Problem Statement

Financial institutions face challenges in identifying risky loan applicants, which can lead to increased defaults and financial losses.

The objective of this project is to:

* Analyze customer and loan attributes
* Identify patterns in rejected applications
* Build a predictive model to classify high-risk customers

---

## 🔹 Key Features

* ✅ Data Cleaning & Preprocessing
* ✅ Feature Engineering (Loan Buckets, Customer Vintage)
* ✅ Exploratory Data Analysis (EDA)
* ✅ Predictive Modeling (Logistic Regression)
* ✅ Risk Segmentation & Business Insights

---

## 🔹 Tech Stack

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Tools:** Jupyter Notebook, Git

---

## 🔹 Dataset

* Simulated dataset representing real-world loan data
* Includes:

  * Loan Amount
  * Customer Vintage
  * Number of MFIs
  * Customer Category
  * Application Timestamp
  * Final Status (Approved / Rejected)

---

## 🔹 Exploratory Data Analysis

Key insights derived:

* 📈 Month-wise rejection trends
* 📊 Rejection distribution across customer categories
* 💰 Loan amount vs rejection probability
* 👥 Impact of multiple MFIs on risk

---

## 🔹 Feature Engineering

Created meaningful features to improve model performance:

* Loan Amount Buckets
* Customer Vintage Buckets
* Encoded categorical variables

---

## 🔹 Model Building

* Algorithm: Logistic Regression
* Data Split: 80% Train / 20% Test
* Evaluation Metrics:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

---

## 🔹 Results

* Achieved strong predictive performance in identifying rejected cases
* Key risk indicators:

  * High loan amount (>150K)
  * Customers with multiple MFIs
* Successfully segmented high-risk customer groups

---

## 🔹 Business Impact

* Helps financial institutions reduce risk exposure
* Improves loan approval decision-making
* Enables targeted risk-based customer evaluation

---

## 🔹 Project Structure

```
loan-risk-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── utils.py
│
├── outputs/
│   ├── plots/
│   └── model/
│
├── requirements.txt
├── main.py
├── README.md
└── .gitignore
```

---

## 🔹 How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/loan-risk-analytics.git
cd loan-risk-analytics
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Project

```bash
python main.py
```

---

## 🔹 Future Improvements

* 🔄 Implement advanced models (Random Forest, XGBoost)
* 📊 Build interactive dashboards using Power BI / Tableau
* 🌐 Deploy as a web app using Streamlit
* 📈 Add more features (income, credit score, region)



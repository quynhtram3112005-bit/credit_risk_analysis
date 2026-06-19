# 💳 Credit Risk Analysis using Machine Learning

> Customer Segmentation • Credit Default Prediction • Risk Analytics

📌 This project applies machine learning techniques to analyze customer credit risk, segment borrowers into risk groups, and predict credit default probability. The project combines unsupervised learning (K-Means Clustering) and supervised learning (Classification Models) to support data-driven lending decisions and credit risk management.

---

## 📊 Project Workflow

```text
Credit Risk Dataset
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Customer Segmentation
(K-Means Clustering)
        │
        ▼
Risk Profile Analysis
        │
        ▼
Classification Models
├── Logistic Regression
├── Support Vector Machine (SVM)
└── Decision Tree
        │
        ▼
Model Evaluation
├── ROC Curve
├── AUC
├── Confusion Matrix
└── Accuracy Metrics
        │
        ▼
Business Insights & Recommendations
```

<img width="414" height="300" alt="Screenshot 2026-06-19 at 16 39 21" src="https://github.com/user-attachments/assets/9e37a277-de9e-4ea9-a787-9c219d1f069f" />

---
## 📂 Dataset Information

This project uses the **Credit Risk Dataset**, a publicly available dataset designed for credit risk analysis and default prediction tasks. The dataset contains customer demographic information, financial characteristics, loan details, and credit history records that can be used to evaluate borrower risk profiles and predict potential loan defaults.

### Dataset Characteristics

<img width="522" height="515" alt="Screenshot 2026-06-19 at 16 26 00" src="https://github.com/user-attachments/assets/eb471c48-8d40-497f-bea4-58fc992b5063" />

### Dataset Size

- **32,000+ customer records**
- Multiple financial and demographic features

### Dataset Source

🔗 Kaggle Dataset:

https://www.kaggle.com/datasets/laotse/credit-risk-dataset


## 🎯 Project Overview

Financial institutions face significant challenges in evaluating borrower risk and minimizing loan defaults. Traditional manual assessment methods are often time-consuming, subjective, and difficult to scale.

This project aims to support credit evaluation by leveraging machine learning techniques to:

* Segment customers into meaningful risk groups.
* Identify key factors affecting repayment ability.
* Predict potential default behavior.
* Support lending and credit approval decisions.
* Enhance risk management through data-driven insights.

The analysis was conducted on a credit risk dataset containing more than **32,000 customer records** and multiple financial attributes related to income, loan amount, credit history, home ownership status, and repayment behavior.

---

## 🛠️ Skills & Tools

### 📈 Credit Risk Analytics

* Credit Risk Assessment
* Customer Risk Segmentation
* Credit Default Prediction
* Lending Decision Support
* Risk-Based Customer Classification

### 🤖 Machine Learning

* K-Means Clustering
* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree

### 📊 Model Evaluation

* ROC Curve Analysis
* Area Under Curve (AUC)
* Confusion Matrix
* Accuracy Evaluation
* Precision Analysis
* Cross Validation

### 🧹 Data Analysis

* Data Cleaning
* Data Preprocessing
* Feature Analysis
* Data Visualization
* Business Insight Generation

### ⚙️ Tools

* Orange Data Mining
* Microsoft Excel
* GitHub

---

# 📖 Project Summary

---

## 1️⃣ Business Understanding & Data Preparation

The project begins with understanding the challenges faced by financial institutions in assessing borrower creditworthiness and managing default risk.

A credit risk dataset containing customer financial information was prepared and analyzed. Data preprocessing techniques were applied to improve data quality and ensure model readiness.

### Key Variables

* Customer Income
* Loan Amount
* Loan-to-Income Ratio
* Credit History Length
* Loan Intent
* Home Ownership Status

---

## 2️⃣ Customer Segmentation using K-Means Clustering

### Objective

Identify hidden customer groups based on financial characteristics and repayment capability.

### Method

* Applied K-Means Clustering.
* Grouped customers into distinct risk segments.
* Compared financial characteristics across clusters.

### Customer Segments

### 🟢 Cluster C1 – Lower Risk Customers

Characteristics:

* Higher income levels.
* Better repayment capability.
* Lower financial stress.
* Lower probability of default.

Business Interpretation:

Customers in this segment demonstrate stronger financial capacity and are generally more creditworthy.

### 🔴 Cluster C2 – Higher Risk Customers

Characteristics:

* Lower income levels.
* Higher debt burden.
* Weaker repayment capability.
* Greater likelihood of repayment difficulties.

Business Interpretation:

Customers in this segment require closer monitoring and stricter credit evaluation procedures.


### 📊 Customer Segmentation Result

<img width="523" height="274" alt="Screenshot 2026-06-19 at 16 28 46" src="https://github.com/user-attachments/assets/ded0c811-a026-4ae6-af9a-174108e95335" />
<img width="491" height="241" alt="Screenshot 2026-06-19 at 16 29 47" src="https://github.com/user-attachments/assets/652aa0fc-5f0f-4604-b5ed-0a43e32629a6" />

---

## 3️⃣ Credit Default Prediction

### Objective

Predict whether a customer is likely to default on a loan based on demographic and financial characteristics.

### Classification Models

The following machine learning models were developed and compared:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree

### Model Development Process

```text
Data Preparation
       │
       ▼
Train/Test Split
(70% / 30%)
       │
       ▼
Model Training
       │
       ▼
Prediction
       │
       ▼
Performance Evaluation
```

### Dataset Split

| Dataset      | Records |
| ------------ | ------- |
| Training Set | 3,500   |
| Testing Set  | 1,500   |

### Orange Workflow

<img width="461" height="303" alt="Screenshot 2026-06-19 at 16 31 03" src="https://github.com/user-attachments/assets/8b4f1c36-feff-45bc-8fe2-8fa80c9fdefc" />

This workflow demonstrates the end-to-end machine learning pipeline used for model training, prediction, and evaluation.

---

## 4️⃣ Model Evaluation & Business Recommendations

### Evaluation Metrics

To assess model performance, multiple evaluation techniques were applied:

* ROC Curve
* AUC
* Accuracy
* Precision
* Confusion Matrix

### 📈 ROC Analysis

<img width="271" height="366" alt="Screenshot 2026-06-19 at 16 32 16" src="https://github.com/user-attachments/assets/0702be0d-5be5-45cf-9eca-c9da8da4719e" />


### 📉 Confusion Matrix

<img width="245" height="362" alt="Screenshot 2026-06-19 at 16 34 37" src="https://github.com/user-attachments/assets/783e2d2a-9119-4e3f-b5df-26293c1e2ffc" />

### 🏆 Best Performing Model

**Decision Tree**

| Metric    | Result |
| --------- | ------ |
| AUC       | 0.815  |
| Accuracy  | 0.911  |
| Precision | 0.914  |

### Key Findings

✅ Decision Tree achieved the highest overall performance.

✅ Decision Tree generated the lowest number of critical prediction errors.

✅ Machine learning models demonstrated strong capability in identifying potential default customers.

✅ Customer segmentation revealed distinct risk profiles with significant differences in repayment capacity.

### Business Recommendations

* Prioritize high-risk customers for additional review.
* Incorporate predictive models into credit approval workflows.
* Apply risk-based customer segmentation strategies.
* Continuously monitor and retrain models to maintain performance.

---

# 🏆 Key Results

### Business Impact

* Successfully segmented customers into meaningful risk groups.
* Built predictive models for credit default assessment.
* Identified key risk patterns affecting borrower behavior.
* Supported data-driven lending decisions.

### Technical Outcomes

* Implemented both unsupervised and supervised learning approaches.
* Evaluated multiple machine learning algorithms.
* Compared model performance using industry-standard metrics.
* Identified Decision Tree as the best-performing model.

---

# 🎓 Key Learning Outcomes

Through this project, I gained practical experience in:

* Credit Risk Analytics
* Customer Segmentation
* Credit Default Prediction
* Machine Learning Model Evaluation
* Risk-Based Decision Making
* Data-Driven Financial Analysis
* Business Insight Generation

---

# 📂 Repository Structure

```text
credit-risk-analysis/
│
│
├── data/
│   ├── credit_risk_5000.csv
│   ├── credit_risk_70.csv
│   └── credit_risk_30.csv
│
├── orange/
│   └── credit_risk_orange.ows
│
├── report/
│   └── REPORT_CREDIT_RISK_ANALYSIS.pdf
│
└── README.md
```

---

# 👩‍💻 Author

**Nguyen Thi Quynh Tram**

University of Economics Ho Chi Minh City (UEH)


```
```

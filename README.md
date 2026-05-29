#  Financial Fraud Detection Using PySpark
### Big Data Analytics Project

---

##  Problem Statement

Financial fraud is one of the most significant threats to the global banking and financial ecosystem. With millions of transactions occurring every second, traditional fraud detection methods—relying on rule-based systems and batch processing—are no longer sufficient. Fraudulent activities such as unauthorized fund transfers, cash-outs, and identity theft cause billions of dollars in losses annually.

This project addresses the challenge of **detecting fraudulent financial transactions in real-time using Big Data Analytics with Apache PySpark**. The dataset represents mobile money transaction records, where each transaction is labeled as either fraudulent (`isFraud=1`) or legitimate (`isFraud=0`). The class imbalance (fraud is rare) and the volume of data make this a classic Big Data problem that benefits from distributed computing.

---

##  Objectives

1. **Data Ingestion & Exploration** — Load and explore a large financial transaction dataset using PySpark's distributed DataFrame API.
2. **Exploratory Data Analysis (EDA)** — Understand data distribution, transaction types, fraud patterns, and class imbalance using PySpark SQL and visualizations.
3. **Data Preprocessing & Feature Engineering** — Clean missing values, encode categorical features, engineer meaningful features, and prepare data for ML pipelines.
4. **Handling Class Imbalance** — Apply oversampling / undersampling strategies to handle the skewed fraud-to-legitimate transaction ratio.
5. **Model Building** — Train multiple ML classifiers (Logistic Regression, Random Forest, Gradient Boosted Trees) using PySpark MLlib.
6. **Model Evaluation** — Evaluate models using precision, recall, F1-score, ROC-AUC, and confusion matrices to select the best performer.
7. **Insights & Reporting** — Draw actionable insights about fraud patterns and model performance.

---

##  Big Data Principles Applied

| Principle | Application |
|-----------|-------------|
| **Volume** | Millions of transaction records processed distributedly |
| **Velocity** | Simulated real-time-like streaming ingestion |
| **Variety** | Mixed types: numerical, categorical, timestamp-like features |
| **Veracity** | Handling missing data and anomalies |
| **Value** | Fraud detection saving financial losses |

---

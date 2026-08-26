# 🛠️ Applied Machine Learning & Kaggle Sandbox

A structured repository tracking my engineering progress across 8 distinct machine learning workloads, Kaggle competitions, and academic milestones. Each project focuses on a unique core competency, moving from classic classification to managing high-dimensional features and handling heavily imbalanced datasets.

---

## 📅 Roadmap & Project Breakdown

| Project # | Project Focus | Core Competency | Timeline | Dataset Source / Link |
| :--- | :--- | :--- | :--- | :--- |
| **01** | Titanic: Machine Learning from Disaster | Classic Binary Classification | 1–5 Days | [Kaggle Titanic](https://www.kaggle.com/competitions/titanic) |
| **02** | Hotel Booking Demand | Operational Forecasting & EDA | 1–5 Days | [Kaggle Hotel Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) |
| **03** | Porto Seguro’s Safe Driver Prediction | Imbalanced Data Handling | 1–5 Days | [Kaggle Safe Driver](https://www.kaggle.com/competitions/porto-seguros-safe-driver-prediction) |
| **04** | High-Dimensional Datascape | Advanced Feature Selection | 1–3 Days | [Kaggle Datascape](https://www.kaggle.com/datasets/krishd123/high-dimensional-datascape) |
| **05** | Kaggle Playground: Series S6E8 | Predicting Smartphone Addiction | 1–5 Days | [Kaggle S6E8](https://www.kaggle.com/competitions/playground-series-s6e8) |
| **06** | Kaggle Playground: Series S4E5 | Flood Prediction Regression | 1–5 Days | [Kaggle S4E5](https://www.kaggle.com/competitions/playground-series-s4e5) |
| **07** | Kaggle Playground: Series S6E6 | Predicting Stellar Class | 1–5 Days | [Kaggle S6E6](https://www.kaggle.com/competitions/playground-series-s6e6) |
| **08** | College Project: Customer Churn | Strategic Business Classification | Ongoing | Enterprise / Academic Dataset |

---

## ⚙️ Engineering Pipeline Stages

Every project in this repository systematically follows a robust data science pipeline tailored to its specific requirements:
1. **Exploratory Data Analysis (EDA):** Visualizing distributions, finding missing data patterns, and discovering statistical anomalies.
2. **Feature Engineering & Selection:** Cleaning missing records, encoding categorical items, scaling data, or filtering out noisy inputs in high-dimensional settings.
3. **Model Selection:** Evaluating multiple baseline architectures (e.g., Logistic Regression, Random Forests, XGBoost, LightGBM).
4. **Imbalanced Data Handling (Project 03 Focus):** Implementing resampling methods (SMOTE) or tuning class weights to deal with rare event labels.
5. **Validation & Evaluation:** Applying robust stratified K-Fold cross-validation and monitoring specific target metrics (AUC-ROC, F1-Score, R² Score).

---

## 📂 Repository Architecture

```text
├── README.md
├── requirements.txt
├── 01-titanic-classification/
├── 02-hotel-booking-demand/
├── 03-porto-seguro-safe-driver/
├── 04-high-dimensional-datascape/
├── 05-smartphone-addiction-s6e8/
├── 06-flood-prediction-s4e5/
├── 07-stellar-classification-s6e6/
└── 08-college-churn-prediction/
```

---

## 📈 Executive Summary Tracker

| Folder Name | Primary Target | Primary Model | Evaluation Metric | Status |
| :--- | :--- | :--- | :--- | :--- |
| `01-titanic-classification` | Passenger Survival | Random Forest | Accuracy | ⏳ In Progress |
| `02-hotel-booking-demand` | Booking Cancellation | LightGBM | F1-Score | 🛑 Todo |
| `03-porto-seguro-safe-driver`| Claim Filed Status | XGBoost | Normalized Gini / AUC | 🛑 Todo |
| `04-high-dimensional-datascape`| Target Target | Ridge Classifier | Accuracy / Feature Drop | 🛑 Todo |
| `05-smartphone-addiction-s6e8`| Addiction Level | CatBoost | Multi-Class LogLoss | 🛑 Todo |
| `06-flood-prediction-s4e5` | Flood Probability | Linear/XGBoost | R² Score | 🛑 Todo |
| `07-stellar-classification-s6e6`| Stellar Class | Gradient Boosting| Macro F1-Score | 🛑 Todo |
| `08-college-churn-prediction` | Account Churn | Logistic Regression| Precision / Recall | 🛑 Todo |

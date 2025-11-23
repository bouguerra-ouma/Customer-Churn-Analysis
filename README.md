# Customer Churn Analysis and Prediction

## Project Overview
This project focuses on analyzing customer churn and building predictive models to identify customers likely to leave a company. The goal is to help businesses implement retention strategies and improve customer satisfaction.

The analysis includes:
- Exploratory Data Analysis (EDA) to understand trends and patterns
- Data preprocessing and feature engineering
- Comparison of multiple machine learning models for churn prediction
- Evaluation of model performance

---

## Folder Structure
Customer-Churn-Analysis/
│
├── notebooks/
│ └── task1.ipynb
│ └── task2_3.ipynb
│ └── task4_5_6.ipynb
  
│
├── datasets/
│ ├── Telco_Customer_Churn.csv
│ └── Telco_Customer_Churn_clean.csv
│ └── Telco_Customer_Churn_feature_selected.csv
│
└── README.md # Project description

---

## Datasets
- All datasets are located in the `datasets/` folder.
- Please ensure your notebook uses **relative paths** to access the datasets, for example:

```python
import pandas as pd

df = pd.read_csv("../datasets/dataset1.csv")

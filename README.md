## 📌 Overview

This project aims to analyze and predict healthcare costs across different jurisdictions, age groups, and medical conditions in Canada using machine learning. Our goal is to support data-driven decisions for efficient healthcare resource allocation and cost management.

We used data from the **Canadian Institute for Health Information (CIHI)** from 2017 to 2022, and built a predictive model that estimates patient healthcare costs with high accuracy.

## 🎯 Objectives

- Analyze trends in healthcare cost data across provinces, age groups, and medical conditions.
- Build a machine learning model to predict individual healthcare costs.
- Create an interactive dashboard using Tableau.
- Deploy a real-time cost prediction tool via a web interface using Flask.

## 📊 Dataset

- Source: Canadian Institute for Health Information (CIHI)
- Timeframe: 2017–2022
- Features: Age, Length of stay, Diagnosis codes, Geographic region, Hospital cost, Physician cost

## 🔍 Exploratory Data Analysis

- Visualized cost distribution across provinces
- Boxplots and heatmaps to reveal correlations and trends
- Observed higher costs in Newfoundland and in older age groups

## 🧪 Statistical Analysis

- **Chi-square Test**: Age group and jurisdiction are dependent
- **ANOVA**: Significant differences in hospital costs across age groups

## ✅ Feature Selection

- Used **Recursive Feature Elimination (RFE)** and **embedded methods**
- Key features: Physician cost, Hospital cost, Length of stay, Age

## 🤖 Model Building

- Algorithm: **Random Forest Regressor**
- Tools: PyCaret, scikit-learn
- Performance:
  - **R² Score**: 0.99
  - **MSE**: 707

## 🚀 Deployment

- Built a **Flask web app** to input patient data and get cost predictions
- Deployed model accessible via user-friendly interface

## 📈 Results & Insights

- Northwest Territories had the highest average patient costs
- Adults and pediatric cases showed highest hospital costs
- Healthcare costs rose steadily, peaking during 2020–2021

## 🔧 Tools & Technologies

- Python, Jupyter Notebooks
- PyCaret, scikit-learn
- Tableau
- Flask




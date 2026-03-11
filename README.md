# Valary Kones_Portfolio
Data Science Portfolio
This repository contains selected data science projects demonstrating skills in data cleaning, exploratory data analysis (EDA), machine learning, and data visualization. The projects focus on transforming real-world datasets into actionable insights using Python and modern data analysis tools.

---
# Project 1: Creating County-Level Acute Food Insecurity Early Warning System (Kenya)

**Project Overview**

This project develops a **county-level early warning system to predict acute food insecurity (IPC Phase 3 or worse) in Kenya one month in advance**. The objective is to identify counties at high risk of food insecurity using historical data and machine learning models, enabling earlier policy and humanitarian response.

To build the prediction system, multiple machine learning models were trained and evaluated, including:

- Logistic Regression
- Random Forest
- XGBoost

These models were applied to a multi-source dataset combining **climate indicators, conflict data, and market price information** to capture factors associated with food insecurity. Model performance was evaluated using classification metrics such as **precision, recall, F1-score, and ROC-AUC** to determine the most effective approach for early risk detection.

**Deployment**

The final model was **deployed on Hugging Face Spaces** as an interactive application. The deployed tool includes a **dashboard interface** that allows users to explore county-level predictions and visualize food insecurity risk trends.

---

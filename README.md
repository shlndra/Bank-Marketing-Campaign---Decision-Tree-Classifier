# Bank Marketing Campaign - Decision Tree Classifier

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-yellow)

A machine learning project that predicts whether a bank customer will subscribe to a term deposit based on demographic and behavioral data, using a Decision Tree Classifier.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Visualizations](#-visualizations)
- [Contributing](#-contributing)
- [License](#-license)

## 🌟 Project Overview
This project builds a predictive model using:
- Decision Tree Classifier
- Advanced feature engineering
- Hyperparameter tuning with GridSearchCV
- Handling class imbalance with SMOTE
- Model interpretation with SHAP values

## 📊 Dataset
The Bank Marketing Dataset from UCI Machine Learning Repository:
- `bank-full.csv` (45,211 records)
- 16 input features + 1 target variable (`y`)
- Contains demographic, financial, and campaign-related attributes

Key statistics:
- 11.7% subscription rate (highly imbalanced)
- Features include age, job, education, contact type, etc.

## 🔍 Features
### Main Features Used:
- **Demographic**: age, job, marital status, education
- **Financial**: balance, housing loan, personal loan
- **Campaign**: contact type, duration, previous outcomes

### Engineered Features:
- Age groups (binned categories)
- Contact frequency categories
- Previous success indicator

## 🛠 Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/bank-marketing-prediction.git
cd bank-marketing-prediction

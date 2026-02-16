# Titanic Survival Prediction 🚢

This repository contains a complete, end-to-end Machine Learning project to predict passenger survival on the Titanic. The project covers everything from data exploration to model deployment-ready optimization.

## 📌 Project Overview
The goal is to predict whether a passenger survived or not based on features like age, sex, passenger class, and more. This is a binary classification problem solved using **Scikit-Learn**.

## 🛠️ Workflow & Key Features

### 1. Exploratory Data Analysis (EDA)
- [cite_start]Analyzed data distributions and identified survival patterns[cite: 2].
- [cite_start]Visualized survival rates based on **Gender** and **Pclass** using Seaborn and Matplotlib[cite: 2].
- [cite_start]Identified missing values and feature correlations[cite: 2].

### 2. Data Cleaning & Preprocessing
- [cite_start]**Missing Value Imputation:** Used `SimpleImputer` to fill missing age values with the median[cite: 2, 4].
- [cite_start]**Feature Selection:** Dropped redundant features like `Cabin`, `Name`, and `Ticket` to prevent overfitting[cite: 2, 4].
- [cite_start]**Categorical Encoding:** Converted categorical text data into numerical format using `LabelEncoder`[cite: 2].

### 3. Model Building & Comparison
- [cite_start]Evaluated multiple models including **Logistic Regression** and **Random Forest**[cite: 4, 5].
- [cite_start]Used a 60/20/20 split for Training, Validation, and Testing sets[cite: 3, 5].

### 4. Hyperparameter Optimization
- [cite_start]Performed **GridSearchCV** to find the best settings for the Random Forest model[cite: 4].
- [cite_start]Implemented **5-fold Cross-Validation** to ensure model stability and reliability[cite: 3].

## 📊 Final Performance (Test Set)
The optimized Random Forest model achieved the following results on the unseen test set:

| Metric    | Score  |
| :-------- | :----- |
| **Accuracy** | **82.7%** |
| **Precision** | **85.7%** |
| **Recall** | **71.1%** |

## 📂 Project Structure
```text
├── data/                   # Raw and cleaned datasets
├── notebooks/              # Jupyter Notebooks for EDA and Modeling
├── scripts/                # Final Python scripts for production
├── venv/                   # Virtual environment
└── README.md               # Project documentation

```

## 💻 Tech Stack
- Languages: Python

- Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

- Tools: PyCharm, Jupyter Notebook, Git

---

Created by **Dhanushka Rathnayaka** - IT Undergraduate at ITUM
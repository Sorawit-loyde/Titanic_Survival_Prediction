# Titanic Survival Prediction Project

This project provides an educational guide to predicting passenger survival on the Titanic using the classic Titanic dataset. It features a highly structured Jupyter Notebook that walks through the entire data science pipeline with detailed explanations.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation and Setup](#installation-and-setup)
- [Key Features](#key-features)
- [Dataset](#dataset)
- [Results](#results)

## Project Overview
The goal of this project is to build a predictive model that answers the question: "what sorts of people were more likely to survive?" using passenger data (ie name, age, gender, socio-economic class, etc).

## Installation and Setup

### 1. Prerequisites
Ensure you have Python 3.7+ installed on your system. You will also need a Jupyter environment (like VS Code with Jupyter extension, or JupyterLab).

### 2. Dependency Installation
You can install all required libraries using pip:

```bash
pip install kagglehub numpy pandas seaborn scikit-learn matplotlib
```

### 3. Running the Project
1. Clone or download this repository.
2. Open the `Titanic_Survival_Prediction-2.ipynb` notebook in your preferred environment.
3. Run the cells sequentially to see the analysis and model building process.

## Key Features
- **Deep EDA**: Comprehensive exploratory data analysis with visual insights.
- **Data Cleaning**: Professional handling of missing values and feature engineering.
- **Comparative Modeling**: Includes both a manual rule-based model and a tuned Logistic Regression machine learning model.
- **Educational Annotations**: Every cell is explained in detail, making it perfect for learning data science fundamentals.

## Dataset
This project uses the Titanic dataset hosted on Kaggle. It is loaded automatically via `kagglehub`.

- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data)
- **Features**:
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Passenger gender
- **Age**: Age in years
- **SibSp**: # of siblings / spouses aboard
- **Parch**: # of parents / children aboard
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Results
The final Logistic Regression model achieves approximately **80%+ accuracy** on the test set after hyperparameter tuning and cross-validation.

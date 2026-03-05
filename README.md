# Titanic Survival Prediction using Logistic Regression

## Overview
This project demonstrates a basic machine learning workflow using the Titanic dataset.  
The goal is to predict whether a passenger survived or not using Logistic Regression.

The project includes:
- Data loading
- Data preprocessing
- Handling missing values
- Encoding categorical variables
- Train-test split
- Model training
- Model evaluation

## Dataset
The dataset used is the **Titanic dataset** available in the Seaborn library.

Main features used:
- pclass
- sex
- age
- sibsp
- parch
- fare
- embarked

Target variable:
- survived (0 = Did not survive, 1 = Survived)

## Technologies Used
- Python
- Pandas
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Workflow

### 1. Import Libraries
```python
import pandas as pd
import seaborn as sns

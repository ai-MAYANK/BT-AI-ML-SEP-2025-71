# AI/ML Assignment – Badkul Technology

Assignment completed for Badkul Technology Pvt Ltd

---

## Project Overview
This repository contains the AI/ML Assignment, consisting of two tasks:

- **Task 1:** Classification on Titanic dataset – predict passenger survival
- **Task 2:** Regression on House Price dataset – predict house prices

Each task demonstrates a complete ML workflow including data loading, cleaning, preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization.

---

## Repository Structure
```
BT-AI-ML-SEP-2025-71/
├── Task 1 - Data Preprocessing & Classification/
│   ├── titanicdataset.ipynb
│   └── train.csv
├── Task 2 - Regression/
│   ├── house_price.ipynb
│   ├── train_001.csv
│   └── test.csv
├── .gitignore
└── README.md
```
---

## Features

### Task 1 – Titanic Dataset Classification
**Objective:** Predict whether a passenger survived the Titanic disaster  
**Dataset:** `train.csv` (included in folder)  
**Source:** Downloaded from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic) as per Badkul Technology instructions


**Workflow:**
1. Data Loading & Exploration (EDA)
2. Data Cleaning & Preprocessing
   - Handling missing values
   - Encoding categorical variables (Label Encoding, One-Hot Encoding)
   - Feature selection
3. Model Training
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
4. Model Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
5. Visualization of model predictions

**Results:** Logistic Regression and Random Forest achieved the best performance

---

### Task 2 – House Price Regression
**Objective:** Predict house prices using numerical and categorical features  
**Dataset:** `train_001.csv` and `test.csv` (included in folder)  
**Source:** Downloaded from [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) as per Badkul Technology instructions


**Workflow:**
1. Data Loading & Exploration (EDA)
2. Data Cleaning & Preprocessing
   - Handling missing values
   - Feature scaling
   - Encoding categorical variables
3. Model Training
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
4. Model Evaluation
   - Mean Squared Error (MSE)
   - R² Score
5. Visualization of predictions vs actual prices

**Results:** Random Forest and XGBoost performed the best

---

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Jupyter Notebook

---

## Install Dependencies
Before running the notebooks, make sure to install all required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
---

## How to Run

### Task 1 – Titanic Classification
```bash
cd "Task 1 - Data Preprocessing & Classification"
jupyter notebook titanicdataset.ipynb
```

### Task 2 – House Price Regression
```bash
cd "Task 2 - Regression"
jupyter notebook house_price.ipynb
```



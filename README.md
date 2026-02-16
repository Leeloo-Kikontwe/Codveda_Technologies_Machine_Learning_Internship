# Machine Learning Internship Project at Codveda Technologies

This repository contains the tasks completed as part of a machine learning internship. The goal is to demonstrate understanding and implementation of various machine learning techniques on different datasets, including regression, classification, and clustering.

## Dataset
**Note**: Datasets were provided for internship purposes and are not included in this repository.
- For Level 1 Task 1, the dataset used is a **House Predication dataset**.
-  For Level 1 Task 2, the dataset used is a **House Prediction dataset** containing numerical features to predict house prices.
-  For Level 2 Task 1, the dataset used is a Telecom Customer Churn dataset for binary classification.
-For Level 2 Task 2, the dataset used is an iris dataset.

## Completed Tasks
Here are the 6 tasks included in this repository:
## Level 1
### **Task 1: Data Preprocessing for Machine Learning**
- Added feature names to the dataset.
- Handled missing data by checking for null values (none were found).
- Separated input features (X) and target variable (y).
- Verified that all features are numeric; no encoding required.
- Split the dataset into training (80%) and testing (20%) sets.
- Standardized numerical features using `StandardScaler`.
- Verified correctness of standardization (mean ≈ 0, std = 1).
- **Tools:** Python, pandas, scikit-learn  
- **Notebook:** `Task1/Task1_Level1.ipynb`
### **Task 2: **Build a Simple Linear Regression Model**
- Loaded a dataset and preprocessed it.
- Trained a linear regression model using scikit-learn.
- Interpreted the model coefficients.
- Evaluated the model using r2_score, mean_absolute_error (MAE) and mean squared
error (MSE).
- **Tools:** Python, pandas, scikit-learn  
- **Notebook:** `Task2/Task2_Level1.ipynb`
### **Task 2: **Build a Simple Linear Regression Model**
- Loaded a dataset and preprocessed it.
- Trained a linear regression model using scikit-learn.
- Interpreted the model coefficients.
- Evaluated the model using r2_score, mean_absolute_error (MAE) and mean squared
error (MSE).
- **Tools:** Python, pandas, scikit-learn  
- **Notebook:** `Task2/Task2_Level1.ipynb`
- 
## Level 2
### **Task 1: **Logistic Regression for Binary Classification**
- Loaded and preprocessed the Telecom Churn Prediction datasets (churn-bigml-80 and churn-bigml-20).
- Trained a logistic regression model using scikit-learn.
- Evaluated the model using metrics such as accuracy, precision, recall, and the ROC curve.
- Interpreted model coefficients and the odds ratio.
- Visualized the ROC curve using matplotlib.
- **Tools:** Python, pandas, scikit-learn, matplotlib
- **Notebook:** `Task3/Task1_Level2.ipynb`
### **Task 2: **Decision Trees for Classification**
- Trained a decision tree on the iris dataset. 
- Visualized the tree structure using plot_tree.
- Pruned the tree to prevent overfitting using criterion="entropy", ccp_alpha, min_samples_leaf.
- Evaluated the model using some classification metrics.
- **Tools:** Python, pandas, scikit-learn, matplotlib, seaborn.
- **Notebook:** `Task4/Task2_Level2.ipynb`


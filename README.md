# Telco-Customer-Churn-Ensemble-Learning
# Telco Customer Churn Prediction using Ensemble Learning

This project focuses on predicting customer churn using the **Telco Customer Churn dataset** and applying different Machine Learning classification models, with a focus on **Ensemble Learning** techniques.

## Project Objective

The main goal is to build and compare different classification models to predict whether a customer is likely to churn.

The project covers the complete Machine Learning workflow, from data preprocessing to model evaluation.

## Dataset

The dataset used in this project is the **Telco Customer Churn dataset** from Kaggle.

It contains information about customers, their services, account details, and whether they left the company.

**Target Variable:** `Churn`

- `Yes` → Customer churned
- `No` → Customer did not churn

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

##Project Workflow

### 1. Exploratory Data Analysis
- Examined the target variable distribution.
- Checked the data types and dataset structure.
- Analyzed the class distribution of customer churn.

### 2. Data Cleaning
- Removed the `customerID` identifier.
- Converted `TotalCharges` to a numeric feature.
- Handled missing values.
- Checked for duplicate records.

### 3. Data Preprocessing
- Encoded the target variable.
- Applied One-Hot Encoding to categorical features.
- Split the dataset into training and testing sets.
- Applied feature scaling where required.

### 4. Machine Learning Models

The following models were trained and compared:

- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Voting Classifier

### 5. Model Evaluation

Models were compared using **Accuracy**, and the selected best-performing model was further evaluated using:

- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

## Ensemble Learning

The project focuses mainly on ensemble methods, including:

- **Random Forest** – combines multiple decision trees using an ensemble approach.
- **AdaBoost** – sequentially combines weak learners by focusing on previous errors.
- **Gradient Boosting** – builds models sequentially to improve previous predictions.
- **Voting Classifier** – combines predictions from different machine learning models.

## Results

The models were compared based on their classification accuracy to identify the best-performing model on the test set.

The final notebook also provides a detailed evaluation of the selected model using a confusion matrix and classification metrics.

## 📁 Project Structure

```text
Telco-Customer-Churn-Ensemble-Learning/
│
├── Telco_Customer_Churn_Ensemble_Learning.ipynb
└── README.md

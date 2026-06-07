# CodeSoft_Credit-Card-Fraud-Detection
Credit Card Fraud Detection using Logistic Regression and Exploratory Data Analysis (EDA).
# Credit Card Fraud Detection Using Logistic Regression

## Project Overview

Credit card fraud is one of the major challenges faced by financial institutions due to the increasing number of digital transactions. Detecting fraudulent transactions accurately is essential to minimize financial losses and enhance transaction security.

This project focuses on building a Machine Learning model to identify fraudulent credit card transactions using Logistic Regression. The dataset contains transaction details, customer information, merchant details, geographic information, and fraud labels. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

---

## Objectives

- Analyze credit card transaction data.
- Perform Exploratory Data Analysis (EDA) to understand transaction patterns.
- Handle missing values and preprocess the dataset.
- Encode categorical features and scale numerical features.
- Build a Logistic Regression model for fraud detection.
- Evaluate model performance using multiple classification metrics.

---

## Dataset Information

The dataset contains information related to credit card transactions, including:

- Merchant Information
- Transaction Category
- Transaction Amount
- Customer Demographics
- Geographic Coordinates
- Transaction Timestamp
- Fraud Label (Target Variable)

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

The dataset is highly imbalanced, with fraudulent transactions representing only a small percentage of the total transactions.

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

### Class Distribution Analysis
- Distribution of fraudulent and legitimate transactions.
- Identification of class imbalance.

### Transaction Amount Analysis
- Distribution of transaction amounts.
- Comparison of transaction amounts between fraud and non-fraud transactions.

### Category-wise Analysis
- Most common transaction categories.
- Fraud rates across different transaction categories.

### Demographic Analysis
- Gender-wise transaction analysis.
- Age distribution of customers.

### Geographic Analysis
- Customer location visualization using latitude and longitude.

### Correlation Analysis
- Correlation heatmap of numerical features.
- Identification of features associated with fraudulent transactions.

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removal of unnecessary columns.
- Handling missing values.
- Conversion of date of birth into customer age.
- Encoding categorical variables.
- Feature scaling using StandardScaler.
- Splitting data into training and testing datasets.

---

## Machine Learning Model

### Logistic Regression

Logistic Regression was used as the classification algorithm for fraud detection.

Reasons for selecting Logistic Regression:

- Simple and interpretable model.
- Effective for binary classification problems.
- Performs well on imbalanced datasets when class weights are applied.
- Computationally efficient.

---

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

### Performance Results

| Metric | Value |
|----------|----------|
| Accuracy | 94.80% |
| ROC-AUC Score | 0.846 |
| Fraud Recall | 74% |

The model successfully identified a significant proportion of fraudulent transactions despite the highly imbalanced nature of the dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Logistic Regression Model Training
7. Model Evaluation
8. Fraud Prediction

---

## Key Features

- Comprehensive Exploratory Data Analysis
- Fraud Pattern Identification
- Feature Engineering
- Data Visualization
- Binary Classification using Logistic Regression
- Model Performance Evaluation

---

## Future Improvements

- Experiment with Decision Trees and Random Forests.
- Apply advanced imbalance handling techniques.
- Implement Hyperparameter Tuning.
- Develop a real-time fraud detection system.
- Deploy the model using Flask or Streamlit.

---

## Conclusion

This project demonstrates the application of Machine Learning for credit card fraud detection. Through data preprocessing, exploratory data analysis, and Logistic Regression modeling, the system was able to effectively identify fraudulent transactions. The results highlight the importance of using evaluation metrics beyond accuracy when working with highly imbalanced datasets.

---

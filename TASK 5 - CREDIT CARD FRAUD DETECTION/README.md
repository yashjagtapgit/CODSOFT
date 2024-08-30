# TASK 5 - CREDIT CARD FRAUD DETECTION
**Codsoft Data Science Internship**

> Author: Yash Jagtap

> Batch: AUGUST BATCH A67

> Domain: Data Science

## Aim
The aim of this project is to build a machine learning model to identify fraudulent credit card transactions. This involves preprocessing the data, handling class imbalance, and optimizing the model's performance to accurately classify transactions as fraudulent or genuine.

## Libraries Used
The following important libraries were used for this project:
- numpy
- pandas
- seaborn
- matplotlib.pyplot
- sklearn.model_selection.train_test_split
- sklearn.ensemble.RandomForestClassifier
- imblearn.over_sampling.SMOTE

## Dataset
The dataset contains 284,807 transactions with 31 features including:
- Time: Time elapsed between this transaction and the first transaction in the dataset.
- V1-V28: Principal components obtained from a PCA transformation.
- Amount: Transaction amount.
- Class: Target variable where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction.

## Data Exploration and Preprocessing
- The dataset was loaded using pandas, and initial exploration was conducted using `df.head()`, `df.info()`, and `df.describe()`.
- Class imbalance was addressed using SMOTE (Synthetic Minority Over-sampling Technique).
- Feature engineering was conducted to identify the most important features correlated with fraudulent transactions.

## Model Training
- A Random Forest classifier was trained using the oversampled data.
- The model was tuned and optimized to improve its precision, recall, and F1-score.

## Model Evaluation
- The model was evaluated using metrics such as accuracy, precision, recall, and F1-score, demonstrating its effectiveness in identifying fraudulent transactions.

## Model Deployment
- The trained model can be used to monitor and detect fraudulent transactions in real-time.

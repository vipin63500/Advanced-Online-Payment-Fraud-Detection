# Advanced-Online-Payment-Fraud-Detection

**Overview**
 - This project focuses on detecting fraudulent transactions in online payment systems. It employs machine learning techniques like Logistic Regression and Random Forest to identify potentially fraudulent 2 - 2- 2-transactions. The project handles class imbalance using SMOTE and includes Exploratory Data Analysis (EDA) to gain insights into transaction patterns.

**Features**
 - Data Cleaning (handling missing values, outliers, and balancing the dataset)
 - Feature Engineering (creating features like balanceOrigDiff, balanceDestDiff)
 - Multicollinearity Check (using VIF to reduce feature redundancy)
 - Model Training using Logistic Regression and Random Forest

**Hyperparameter tuning with GridSearchCV**
 - Model Evaluation (accuracy, precision, recall, F1-score, and ROC AUC)
 - EDA including Correlation Analysis, Time-Based Analysis, and Feature Interactions

**EDA Insights**
- Correlation Analysis to understand relationships between features
 - Feature Interactions to uncover patterns in the dataset
 - Time-Based Analysis to detect patterns in transaction behavior over time
 - Categorical Feature Analysis to explore the relationship between transaction types and fraud

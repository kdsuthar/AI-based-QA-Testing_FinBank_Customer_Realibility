# FinBank Financial Reliability Prediction: 
## 📝 Overview
FinBank, a retail financial services provider, is striving to better identify financially reliable customers in order to:

1. Minimize default risk.

2. Improve customer retention.

3. Design personalized services.

4. To achieve this, FinBank has collected a wide range of behavioral, transactional, and demographic data from its customer base.

As a Data Analyst or QA Engineer, your mission is to:

1. Clean and preprocess the dataset.

2. Build a machine learning model to predict customer financial reliability.

## Predict the binary outcome:

1 = Financially Reliable

0 = Financially Unreliable

## 📂 Dataset Structure
The dataset consists of two CSV files:

## File	Description: https://jupyter.org/try-jupyter/lab/ or https://jupyter.org/try-jupyter/notebooks/index.html?path=notebooks%2FLoan_Prediction_Analysis.ipynb 
1. train.csv	Contains features and target variable for training the model.
2. test.csv	Contains features only, target variable is not included (for final prediction)

## 📈 Features in train.csv
### Feature	Description
1. ID: Unique identifier for each customer
2. Age: Age of the customer
3. Customer_Segment	Customer tier (e.g., Bronze, Gold, Platinum)
4. Region	Geographical region
5. Preferred_Channel	Interaction preference (Online, Branch, Phone)
6. Employment_Status	Employment category (e.g., Employed, Self-Employed, Unemployed)
7. Annual_Income	Yearly income in USD
8. Spending_Score	Internal metric indicating spending behavior
9. Savings_Amount	Amount saved by the customer
10. Loan_Amount	Outstanding loan amount
11. Customer_Tenure	Years since becoming a customer
12. Credit_Score	Financial credit score
13. Avg_Transaction_Value	Average transaction size
14. Num_Bounced_Checks	Number of checks that bounced
15. Account_Balance	Current balance in the account
16. Referral_Count	Number of customers referred
17. Loyalty_Score	Internal loyalty score
18. Has_Credit_Card	Whether the customer has a credit card (1 = Yes, 0 = No)
19. Has_Loan	Whether the customer has a loan (1 = Yes, 0 = No)
20. target	Label: 1 = Reliable, 0 = Unreliable

## 🧪 Tasks
### ✅ 1. Data Cleaning
1. Identify and handle missing values.

2. Check for and remove duplicate records.

3. Convert categorical variables into numeric (encoding).

### ⚙️ 2. Feature Engineering
1. Create or transform features that may boost predictive power.

2. Normalize or scale numeric features if required.

### 🤖 3. Model Building
1. Train multiple ML algorithms (e.g., Logistic Regression, Random Forest, XGBoost)

2. Use cross-validation for performance evaluation.

3. Optimize hyperparameters for best results.

### 📊 4. Evaluation
1. Evaluate models using metrics like accuracy, precision, recall, and F1 score.

2. Use confusion matrix or ROC-AUC for performance insights.

### 📤 5. Prediction on Test Data
Apply final model to test.csv and output predicted reliability.

### 🛠️ Tech Stack
- Python (Jupyter Notebook)

- Pandas, NumPy

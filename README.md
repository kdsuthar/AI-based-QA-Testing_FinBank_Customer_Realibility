# FinBank Financial Reliability Prediction: 
## 📝 Overview
FinBank, a retail financial services provider, is striving to better identify financially reliable customers in order to:

1. Minimize default risk.

2. Improve customer retention.

3. Design personalized services.

4. To achieve this, FinBank has collected a wide range of behavioral, transactional, and demographic data from its customer base.

As a data scientist, your mission is to:

1. Clean and preprocess the dataset.

2. Build a machine learning model to predict customer financial reliability.

## Predict the binary outcome:

1 = Financially Reliable

0 = Financially Unreliable

## 📂 Dataset Structure
The dataset consists of two CSV files:

## File	Description
train.csv	Contains features and target variable for training the model
test.csv	Contains features only; target variable is not included (for final prediction)

## 📈 Features in train.csv
### Feature	Description
ID	Unique identifier for each customer
Age	Age of the customer
Customer_Segment	Customer tier (e.g., Bronze, Gold, Platinum)
Region	Geographical region
Preferred_Channel	Interaction preference (Online, Branch, Phone)
Employment_Status	Employment category (e.g., Employed, Self-Employed, Unemployed)
Annual_Income	Yearly income in USD
Spending_Score	Internal metric indicating spending behavior
Savings_Amount	Amount saved by the customer
Loan_Amount	Outstanding loan amount
Customer_Tenure	Years since becoming a customer
Credit_Score	Financial credit score
Avg_Transaction_Value	Average transaction size
Num_Bounced_Checks	Number of checks that bounced
Account_Balance	Current balance in the account
Referral_Count	Number of customers referred
Loyalty_Score	Internal loyalty score
Has_Credit_Card	Whether the customer has a credit card (1 = Yes, 0 = No)
Has_Loan	Whether the customer has a loan (1 = Yes, 0 = No)
target	Label: 1 = Reliable, 0 = Unreliable

## 🧪 Tasks
### ✅ 1. Data Cleaning
1. Identify and handle missing values

2.  Remove or treat outliers

3. Check for and remove duplicate records

4. Convert categorical variables into numeric (encoding)

### ⚙️ 2. Feature Engineering
1. Create or transform features that may boost predictive power

2. Normalize or scale numeric features if required

### 🤖 3. Model Building
1. Train multiple ML algorithms (e.g., Logistic Regression, Random Forest, XGBoost)

2. Use cross-validation for performance evaluation

3. Optimize hyperparameters for best results

### 📊 4. Evaluation
1. Evaluate models using metrics like accuracy, precision, recall, and F1 score

2. Use confusion matrix or ROC-AUC for performance insights

### 📤 5. Prediction on Test Data
Apply final model to test.csv and output predicted reliability

### 🛠️ Tech Stack
- Python (Jupyter Notebook)

- Pandas, NumPy

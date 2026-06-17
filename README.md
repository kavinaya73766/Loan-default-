Project Overview:
The Loan Default Prediction System is a data analysis and machine learning project developed to help financial institutions identify borrowers who are likely to default on loans. 
The project uses Exploratory Data Analysis (EDA), Risk Analysis, Logistic Regression, and Dashboard Visualization to study borrower behavior and improve loan
approval decisions.The system analyzes customer information such as income, interest rate, employment length, home ownership, and loan purpose 
to identify patterns related to loan repayment and default risk.

Dataset Information:
Dataset Source
Kaggle – Lending Club Loan Dataset

Dataset Features:
Column Name	     Description
loan_amnt	       Loan amount
term	           Loan duration
int_rate	       Interest rate
annual_inc	     Annual income
emp_length	     Employment length
home_ownership	 Ownership status
purpose	         Loan purpose
grade	Loan       risk grade
loan_status	     Loan repayment status

Target Variable:
Fully Paid
Default

Technologies Used:
Technology	      Purpose
Python	          Programming language
Pandas	          Data manipulation
NumPy            	Numerical operations
Matplotlib	      Data visualization
Seaborn	          Statistical visualization
Plotly	          Interactive dashboard
Scikit-Learn	    Machine learning
Jupyter Notebook	Development environment

Project Workflow:
Data Collection
Data Cleaning
Data Preprocessing
Exploratory Data Analysis (EDA)
Risk Analysis
Feature Selection
Logistic Regression Model
Model Evaluation
Dashboard Visualization
Insights and Conclusion

Exploratory Data Analysis (EDA):
EDA helps understand the dataset and identify important patterns.

EDA Activities:
Checking missing values
Statistical summary
Distribution analysis
Correlation analysis
Outlier detection
Loan default comparison
Important Analysis
Income distribution
Loan amount distribution
Interest rate trends
Loan status comparison
Employment analysis

Risk Analysis:
Borrowers are classified into risk categories based on interest rates and financial behavior.

Risk Level	      Interest Rate
Low Risk	        Below 10%
Medium Risk	      10% – 18%
High Risk	        Above 18%

High-Risk Indicators:
Low annual income
High interest rate
Short employment length
High loan amount
Poor loan grade

Machine Learning Models:
The project uses Machine Learning to predict borrower risk and loan behavior.

Model Used:
Logistic Regression
Purpose:
Predict whether a borrower may default
Identify high-risk borrowers
Improve decision-making

Logistic Regression:
Logistic Regression is used as a classification algorithm to predict loan status.
Input Features:
Annual Income
Interest Rate
Loan Term
Employment Length
Output
Fully Paid
Default
Workflow
Loan Default Risk Factors

Key factors influencing loan default prediction.

0
25
50
75
100
Interest Rate
Annual Income
Employment Length
Loan Amount
Loan Grade

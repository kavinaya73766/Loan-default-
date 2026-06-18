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

Data Visualizations

The project includes multiple visualizations for better understanding.

Visualizations Used:

Bar Charts
Histograms
Scatter Plots
Box Plots
Heatmaps
Interactive Plotly Charts

Dashboard Features:

Loan distribution
Default comparison
Income analysis
Interest rate trends
Dynamic filtering

Key Findings:

Higher interest rates increase default risk.
Low-income borrowers show higher default probability.
Employment length affects repayment behavior.
Certain loan purposes have higher default rates.
High loan amounts are associated with increased risk.

<img width="762" height="505" alt="image" src="https://github.com/user-attachments/assets/04bd612d-e40f-4cdf-bd06-c98af8979574" />

<img width="915" height="600" alt="image" src="https://github.com/user-attachments/assets/9489ec80-1387-4e82-a942-2c3fd533244a" />

<img width="922" height="595" alt="image" src="https://github.com/user-attachments/assets/423e4ff7-481f-4c00-aff8-c3a490043265" />

<img width="922" height="601" alt="image" src="https://github.com/user-attachments/assets/32675508-f9a9-4a55-950c-a005f87f53f9" />

<img width="862" height="587" alt="image" src="https://github.com/user-attachments/assets/23cf9fff-4447-4451-b68f-56d9ad6297cc" />

<img width="932" height="662" alt="image" src="https://github.com/user-attachments/assets/cb47e5aa-f0f1-4808-afcb-213c04871645" />

<img width="1168" height="722" alt="image" src="https://github.com/user-attachments/assets/46a672fb-44af-4f10-87af-5cae01772206" />

<img width="887" height="553" alt="image" src="https://github.com/user-attachments/assets/03fc82ba-67d3-4a3f-93bf-d983f251703d" />

<img width="970" height="606" alt="image" src="https://github.com/user-attachments/assets/6ef7ed6a-a23f-4d3f-aadb-7257105545b4" />

Conclusion:

The Loan Default Prediction System successfully analyzes borrower behavior using EDA and Machine Learning techniques. The project helps financial institutions identify risky borrowers, reduce loan default risk, and improve financial decision-making.

Using Logistic Regression and interactive dashboards, the system provides meaningful insights into loan repayment patterns and supports smarter loan approval strategies.

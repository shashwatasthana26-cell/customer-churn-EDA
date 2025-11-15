Customer Churn Analysis

Overview
This project analyzes customer churn data to uncover insights into customer behavior. Using exploratory data analysis (EDA), it identifies factors influencing churn such as tenure, monthly charges, contract type, and payment method.

Key Insights

High Churn Drivers: 
Electronic check payment method
Monthly contracts
No online security or tech support
Non-senior citizens

Data Trends:
75% of customers have tenure < 55 months
Average monthly charges: USD 64.76; 25% pay > USD 89.85
Higher churn observed for customers with high monthly charges but low total charges due to short tenure

Feature Relationships:
Total charges increase with monthly charges
Churn is higher when monthly charges are high and tenure is low

Data Cleaning & Processing:
Converted TotalCharges to numeric and handled 11 missing values (~0.15%)
Categorized tenure into bins (1–12, 13–24 months, etc.)
Encoded categorical variables and target variable Churn (Yes = 1, No = 0)
Removed unnecessary columns for analysis

Tools & Libraries
Python (Pandas, NumPy)
Matplotlib & Seaborn for visualization
Jupyter Notebook

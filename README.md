Bank Personal Loan Analysis
🚀 Project Overview

This project focuses on analyzing customer data from a bank to understand the key factors influencing whether a customer will accept a personal loan offer. Using data analysis and visualization techniques, the project derives actionable insights that can help banks in targeted marketing and decision-making.

🎯 Objective
Analyze customer behavior and financial attributes
Identify important features affecting personal loan acceptance
Perform data cleaning, transformation, and visualization
Generate insights for business decision-making
📂 Dataset
Total Records: 5000+ customers
Features Include:
Age, Experience, Income
Family size, Education
Credit Card Average (CCAvg)
Mortgage, Securities Account, CD Account
Online banking, Credit Card usage
Target Variable: Personal Loan (0 = No, 1 = Yes)
⚙️ Tech Stack
Language: Python
Libraries:
Pandas, NumPy
Matplotlib, Seaborn, Plotly
Scikit-learn (for preprocessing concepts)
🔍 Project Workflow
1. Data Preprocessing
Removed irrelevant columns (ID, ZIP Code)
Handled invalid values (negative Experience replaced with mean)
Checked for missing values and data consistency
2. Exploratory Data Analysis (EDA)
Visualized data using:
Histograms
Box plots
Distribution plots
Correlation heatmap
Identified relationships between features and loan acceptance
3. Feature Engineering
Converted Education into categories:
Undergraduate, Graduate, Professional
Created new feature:
Account holder category (based on Securities & CD Account)
4. Data Transformation
Applied log transformation on skewed features (Income, CCAvg)
Improved data distribution for better analysis
📊 Key Insights
Customers with higher income are more likely to accept loans
Higher credit card spending (CCAvg) increases loan probability
Customers with CD accounts show higher loan acceptance
Most customers do not hold securities or deposit accounts
📈 Visualizations
Distribution plots for Income and CCAvg
Correlation heatmap between features
Pie charts for education and account categories
Count plots for categorical features vs loan status
🧠 Learnings
Real-world data cleaning and preprocessing
Feature engineering techniques
Understanding customer behavior through data
Importance of visualization in decision-making
🔮 Future Improvements
Build predictive models (Logistic Regression, Random Forest, XGBoost)
Perform feature selection for better accuracy
Deploy as a dashboard or web app
📌 Conclusion

This project demonstrates how data analysis can uncover meaningful patterns in customer behavior. The insights derived can help banks improve loan targeting strategies, leading to better customer engagement and business growth.

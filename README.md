# Loan-Approval-Prediction
Loan Approval Prediction Readme

Loan approval prediction involves the analysis of various factors, such as the applicant’s financial history, income, credit rating, employment status, and other relevant attributes. By leveraging historical loan data and applying machine learning algorithms, businesses can build models to determine loan approvals for new applicants.

Project Overview:
⦁	This project builds a machine-learning solution to predict loan application outcomes using applicant demographics, credit history, employment and income details, loan attributes, and other relevant signals.
⦁	Through rigorous feature engineering, model selection, and validation, the system produces reliable, interpretable predictions that support faster and more consistent underwriting decisions.
⦁	Beyond accuracy, the workflow emphasizes fairness, explainability, and risk-calibrated outputs—enabling lenders to reduce default exposure, streamline processing, and meet regulatory and audit requirements while improving customer experience.



Objectives:
⦁	Analyze loan applicant data to identify key factors influencing loan approval.
⦁	Perform thorough data preprocessing, including missing value treatment, encoding, and outlier handling.
⦁	Visualize data patterns and relationships between applicant attributes and loan status.
⦁	Build a predictive model using Support Vector Machine (SVM) for classification.
⦁	Evaluate model performance and interpret the results for decision-making.



Data Preprocessing Steps:

1.	Missing Value Handling
⦁	Mode imputation for categorical variables (e.g., Gender, Married, Dependents).
⦁	Median imputation for numerical variables like LoanAmount.
⦁	Mode imputation for Credit_History and Loan_Amount_Term.

2) Outlier Detection and Removal
⦁	Used Interquartile Range (IQR) to remove extreme values in income-related columns.

3) Encoding Categorical Features
⦁	Applied One-Hot Encoding to convert categorical data into a numerical format.

4)Feature Scaling
⦁	Used StandardScaler to normalize numeric columns for better model performance.



Exploratory Data Analysis (EDA):
⦁	Loan Status Distribution: Shows the ratio of approved vs rejected loans.
⦁	Gender, Marital Status, and Education Analysis: Helps understand how demographics affect loan outcomes.
⦁	Income & Loan Amount Insights: Box plots and histograms reveal applicant profiles and outliers.
⦁	Credit History & Property Area: Strong indicators influencing loan approval likelihood.
All visualizations were created using Plotly, providing interactive and presentation-ready insights.



Model Development:
⦁	Algorithm Used: Support Vector Machine (SVM)
⦁	Train-Test Split: 80% training and 20% testing data
⦁	Feature Scaling: Standardization applied to numerical columns
⦁	Prediction Output: Classified loan applications as Approved or Not Approved



Model Evaluation:
⦁	The SVM model effectively distinguishes approved and rejected loans based on applicant profiles.
⦁	Results indicate strong correlation between Credit History, Applicant Income, and Loan Amount with loan approval.



Key Insights:
⦁	Applicants with a good credit history have the highest chance of loan approval.
⦁	Self-employed individuals and those with lower income are more likely to face rejection.
⦁	Maintaining a balance between Loan Amount and Applicant Income improves approval probability.



Conclusion:
⦁	This project demonstrates how machine learning can be effectively used to predict loan approvals.
⦁	By applying data preprocessing, visualization, and predictive modeling, it delivers actionable insights to financial institutions and improves credit risk management.

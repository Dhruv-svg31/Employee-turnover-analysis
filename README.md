#Employee-turnover-analysis
End-to-end employee turnover analysis and prediction using Python, EDA, and logistic regression.Google Advanced Data Analytics capstone project on employee turnover analysis and prediction.
This project focuses on analyzing employee turnover and identifying key factors that contribute to attrition using data analytics and machine learning techniques. The goal is to derive actionable insights that can help organizations improve employee retention strategies.

The project was completed as part of the Google Advanced Data Analytics Capstone and follows the PACE (Plan, Analyze, Construct, Execute) framework.

#Problem Statement
Employee turnover is a major challenge for organizations, leading to increased costs and loss of talent. This project aims to:
- Understand the key drivers of employee attrition
- Build a baseline predictive model to identify employees at risk of leaving

#Key Analysis & Insights
- Employees with low satisfaction levels are significantly more likely to leave.
- Workload imbalance (very low or very high average monthly hours) increases attrition.
- Employees handling 3–4 projects show the highest retention.
- Turnover peaks around 3 years of tenure, indicating a critical retention period.
- Promotions strongly reduce attrition, while performance evaluation alone is a weak predictor.

#Tools & Technologies
Python
pandas, numpy
matplotlib
scikit-learn
Logistic Regression
Exploratory Data Analysis (EDA)
Machine Learning Classification

#Modeling Approach
- Built a Logistic Regression model as a baseline classifier
- Evaluated model performance using
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Identified limitations related to class imbalance and recall for attrition cases

#Results
- Achieved 74.7% accuracy on the test dataset
- Model performed well in predicting employees who stayed
- Highlighted the need for advanced models to better identify employees likely to leave

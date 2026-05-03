# Customer-Churn-Prediction
End-to-end churn prediction project using the Telco dataset. Developed a Logistic Regression model in Python to identify at-risk customers with a high ROC-AUC. Exported predictions to an interactive Power BI dashboard featuring DAX-calculated "At-Risk Revenue," prioritized Risk Tiers, and dynamic churn drivers to enable proactive retention.
Project Overview
This project addresses the challenge of customer retention by identifying at-risk subscribers before they leave. Using the IBM Telco dataset, I developed a machine learning pipeline to predict churn and integrated the results into a dynamic Power BI Report. This allows retention teams to prioritize customers based on financial impact and risk probability.
Tech Stack
Language: Python 3.x
Libraries: Pandas, Scikit-learn, NumPy, Matplotlib
Models: Logistic Regression (optimized for interpretability)
Visualization: Power BI Desktop (DAX, Field Parameters)
Key Features
Predictive Modeling: Built a classification model using Logistic Regression to generate churn probabilities for every customer.
Data Pipeline: Cleaned messy data (e.g., handling TotalCharges formatting issues) and managed feature engineering via One-Hot Encoding.
Actionable BI Dashboard:
At-Risk Revenue: A DAX-powered KPI card showing the dollar amount currently at stake.
Risk Tiers: A prioritized "To-Do List" for sales teams, categorizing customers into High, Medium, and Low risk.
Dynamic Churn Drivers: Interactive bar charts using Field Parameters to analyze root causes like contract types and tech support availability.
The Analytical Workflow
Exploratory Data Analysis (EDA): Identified that month-to-month contracts and Fiber Optic users without Tech Support have the highest churn rates.
Model Training: Trained a Logistic Regression model (max_iter=10000) to achieve a high ROC-AUC score.
Data Export: Re-attached unique customerID and original categorical labels to the model's predictions for business readability.
Reporting: Visualized findings in Power BI to translate complex probabilities into an easy-to-use retention tool.
<img width="1292" height="738" alt="cust_churn" src="https://github.com/user-attachments/assets/a33105a7-183b-4e2a-9857-ca9161989c54" />

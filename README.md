# Churn Analysis

📊 Churn Analysis Project Summary
🎯 Project Target

The goal of this project was to design an end-to-end Churn Analysis solution by:

Building a complete ETL process in SQL for structured data management.

Developing an interactive Power BI dashboard for insights.

Using Python for churn prediction modeling.

This project aims to help businesses:

Visualize and analyze customer data across multiple dimensions:

Demographic (Age, Gender, Dependents)

Geographic (State, Region)

Payment & Account Info (Tenure, Payment Method, Contract Type)

Services (Internet, Phone, Streaming, Tech Support)

Study churner profiles to identify areas for marketing campaign interventions.

Predict future churners using machine learning models.

📂 Data Source

The dataset (Customer_Data.csv) contains:

Customer demographics

Account details

Subscription services

Churn status (Yes/No)

⚙️ ETL Process (SQL)

The raw data was cleaned and transformed using SQL queries:

Handling missing values & standardizing categorical values.

Creating customer segments by demographics and geography.

Aggregating data for churn, tenure, and services.

Loading processed tables into a database for BI consumption.

Key SQL transformations included:

TotalCustomers = COUNT of unique customers.

ChurnRate = (Churned Customers / Total Customers) * 100.

NewJoiners = Customers with tenure = 0 or 1 month.

📊 Dashboard (Power BI)

A fully interactive Power BI dashboard was built, featuring:

KPIs: Total Customers, Churned Customers, Churn Rate, New Joiners.

Demographics View: Churn breakdown by gender, senior citizens, dependents.

Geographic View: Regional churn distribution.

Account & Payment View: Churn by contract type, payment method, monthly charges.

Services View: Churn by internet service, streaming, tech support, multiple lines.

👉 Users can filter by region, tenure, and contract type to drill down into churn insights.

🐍 Predictive Modeling (Python)

A machine learning model was developed in Python to predict churners:

Libraries used: pandas, scikit-learn, matplotlib, seaborn.

Steps:

Data preprocessing (encoding categorical variables, scaling).

Train-test split.

Model training using Logistic Regression, Random Forest, and XGBoost.

Model evaluation using Accuracy, Precision, Recall, F1-Score, ROC-AUC.

Final model achieved ~80% accuracy in predicting churn.

📌 Key Insights

High churn rate among customers with month-to-month contracts.

Customers using electronic check payments had significantly higher churn.

Senior citizens and customers without tech support were more likely to churn.

Longer-tenure customers were less likely to churn → retention improves over time.

🚀 Deliverables

SQL Scripts → For ETL and churn data aggregation.

Power BI Dashboard → Interactive churn insights visualization.

Python Notebook → Machine learning churn prediction.

🌐 Sharing

🔗 GitHub Repository → Complete code, SQL scripts, and notebook.
🔗 LinkedIn Post → Project showcase for professional networking.

✨ This project demonstrates how SQL, Power BI, and Python can be integrated to build a robust Customer Churn Analysis & Prediction System that drives data-driven decision-making.
#Screeshot/Demo 
https://github.com/Nikeshyadav005/Churn-Analysis/blob/main/Churn%20image.png
#LinkedIn
https://www.linkedin.com/in/nikesh-yadav-344732310

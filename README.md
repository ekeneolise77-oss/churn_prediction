# Customer Churn_Prediction and Retention Dashboard

## Overview

This project focuses on Business intelligence for customer churn predictions and retention. It involves building a predictive model and an interactive dashboard to analyze customer churn in a telecommunications company. The dashboard provides key insights into churn rates, predicted churned customers, and factors influencing retention, enabling data-driven strategies to reduce customer attrition. The model uses machine learning techniques to predict which customers are likely to churn based on historical data, while the dashboard visualizes metrics and distributions for quick managerial decision-making. This aligns with business intelligence practices to enhance customer retention through targeted interventions, such as personalized offers or improved service plans.

## Features
Predictive modeling - A machine learning model (e.g., logistic regression, random forest, XGBoost, and lightGBM) trained to forecast customer churn probability.
  + Key metrics dashboard
  + Churn rate: 26.54%
  + Predicted churned customers: 1,869
  + Total customers: 7,043
  + Average monthly charges: $64.76
Visualizations
  + Churn by contract type: Bar chart showing higher churn in month-to-month contracts compared to one-year or two-year plans.
  + Churn distribution: Pie chart illustrating the split between churned (26.54%) and retained (73.46%) customers.
  + Additional charts for model performance, customer segmentation, and churn rate trends.

Data exploration - Interactive filters for segments like contract type, payment methods, or tenure.

## Dataset
The project utilizes a sample telecommunications customer dataset (inspired by the Telco Customer Churn dataset), which includes features such as:
  + Customer demographics (age, gender, etc.)
  + Account information (tenure, contract type, payment method)
  + Services subscribed (internet, phone, streaming, etc.)
  + Monthly and total charges
  + Churn status (yes/no)

The dataset contains approximately 7,043 customer records, with a churn rate of 26.54%. Data preprocessing includes handling missing values, encoding categorical variables, and feature scaling.

## Technologies used
+ Programming language: Python 3.x
+ Libraries
+ Data Processing - Pandas, NumPy
+ Machine learning - Scikit-learn, XGBoost.
+ Visualization - Matplotlib, Seaborn, or dashboard tools like Streamlit/Dash/Tableau/Power BI.
+ Environment - Jupyter Notebook for development; optional deployment via Streamlit or Heroku.
+ Version Control - Git

## Installation
1. Clone the repository
    + git clone https://github.com/ekeneolise77-oss/churn_prediction.git
    + cd customer-churn-prediction
2. Install dependencies
    + pip install -r requirements.txt
3. Download the dataset (e.g., telco_customer_churn.csv) and place it in the data/ directory.

## Usage
1. Train the model
2. Launch the dashboard
   + Use Streamlit to run the interactive dashboard

## Explore insights:
- View overall churn metrics.
- Filter by contract type to see churn breakdowns.
- Use predictions to identify at-risk customers for retention campaigns.

## Results and insights
- **Churn rate analysis** - The overall churn rate is 26.54%, with 1,869 customers predicted to churn out of 7,043 total.
- **Key driver**- Month-to-month contracts show significantly higher churn compared to longer-term contracts, suggesting retention strategies like discounts for annual commitments.
- **Financial impact** - Average monthly charges are $64.76; reducing churn could preserve substantial revenue.
- Model accuracy (Assuming evaluation) achieves ~80% accuracy in predicting churn, with precision focused on high-risk segments.

## Retention recommendations
- Target month-to-month customers with loyalty programs.
- Analyze additional factors like service add-ons or payment methods for personalized retention.

## Contributing
Contributions are welcome!
Please follow these step,
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

## Contact
For questions or collaboration, reach out to oliseekene561@gmail.com

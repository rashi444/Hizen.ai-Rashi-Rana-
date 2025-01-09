This project focuses on predicting user churn for an e-commerce platform by analyzing user activities such as views, cart additions, and purchases. The primary goals are to identify users likely to churn and to provide actionable insights into the reasons behind their churn.


Dataset
The analysis utilizes the events.csv dataset, which includes the following key columns:
event_time: Datetime of the event (e.g., 2020-12-01 09:00:00)
event_type: Type of event (view, cart, purchase)
product_id: Identifier of the product
category_id: Identifier of the product’s category
brand: Brand of the product
price: Price of the product
user_id: Identifier of the user performing the event


Objectives
Predict users most likely to churn.
Provide insights into why users churn, focusing on actionable business takeaways.


Approach
Data Inspection & Preprocessing: Load, clean, and prepare the dataset for analysis.
Exploratory Data Analysis (EDA): Analyze user behavior and identify feature relation in event distributions.
Churn Definition: Propose a clear definition of churn based on RFM metrics and threshold (e.g., no purchases in the last 30 days).
Feature Engineering: Create user-level features that capture churn signals, including RFM metrics and session-based metrics.
Predictive Modeling: Build a churn prediction model using machine learning algorithms and evaluate its performance.


Business Recommendations: Suggest strategies for user retention based on modeling insights. [Expert System]


You can implement the code through Google Colab, by downloading my file

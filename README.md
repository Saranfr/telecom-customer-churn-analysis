<img width="1488" height="741" alt="image" src="https://github.com/user-attachments/assets/1b9f9252-9fc8-44d8-a5c7-6e454c96fca3" /># telecom-customer-churn-analysis
Project Overview : 
Telecom Customer Churn Analysis

	This project analyzes customer churn data from a telecom company to identify the key factors influencing customer attrition. Using 	Python for data cleaning and exploratory data analysis (EDA) and Power BI for dashboard development, the project provides 	actionable insights to help businesses improve customer retention and reduce churn.

Dataset Information
	Dataset: Telecom Customer Churn Dataset
	Total Records: 7,043 customers
	Features: 33 customer-related attributes
	Key Variables:
	Customer Demographics
	Contract Type
	Payment Method
	Internet Service
	Monthly Charges
	Tenure Months
	Churn Label
	Churn Reason

The dataset contains customer subscription information and indicates whether a customer has churned or remained with the company.

Business Problem

	Customer churn is one of the major challenges faced by telecom companies, as acquiring new customers is significantly more 	expensive than retaining existing ones.

The objective of this project is to:

	Measure the overall churn rate.
	Identify high-risk customer segments.
	Determine factors contributing to churn.
	Provide data-driven recommendations to improve customer retention.

Analysis Process
1. Data Cleaning
	Inspected data types and missing values.
	Identified missing values in Total Charges and Churn Reason.
	Investigated missing records and validated that missing Total Charges corresponded to customers with zero tenure.
2. Exploratory Data Analysis (EDA)
	Calculated overall churn rate.
	Analyzed churn across:
	Contract Types
	Payment Methods
	Internet Services
	Senior Citizen Status
	Monthly Charges
	Customer Tenure
3. Dashboard Development

Built an interactive Power BI dashboard featuring:

	KPI Cards
	Churn Distribution Analysis
	Contract Analysis
	Payment Method Analysis
	Internet Service Analysis
	Churn Reason Analysis
	Customer Segmentation Analysis
Key Insights
	Overall Churn
	Overall churn rate is 26.54%.
Contract Type
	Month-to-month customers show the highest churn rate (42.7%).
	Two-year contract customers show the lowest churn rate (2.8%).
Payment Method
	Customers using electronic checks have the highest churn rate (45.3%).
Internet Service
	Fiber optic customers exhibit significantly higher churn (41.9%) compared to DSL users.
Customer Tenure
	Churned customers have an average tenure of 17.98 months.
	Retained customers have an average tenure of 37.57 months.
Senior Citizens
	Senior citizens experience a higher churn rate (41.7%) than non-senior customers (23.6%).
Monthly Charges
	Churned customers pay higher average monthly charges ($74.44) than retained customers ($61.27).

Churn Reasons

The leading churn reasons include:

	Poor support experience
	Better competitor offers
	Higher competitor download speeds
	More competitor data plans
	Dashboard Screenshots
	Executive Dashboard
  <img width="1488" height="741" alt="image" src="https://github.com/user-attachments/assets/d290afcf-6595-459b-9958-54798b8ed271" />

  Customer Segmentation Dashboard
<img width="1352" height="748" alt="image" src="https://github.com/user-attachments/assets/3c7cf417-8de7-4965-a3d6-15e0dca6f79d" />

Recommendations

Based on the analysis, the following actions are recommended:

1. Encourage Long-Term Contracts

	Offer discounts and loyalty rewards to encourage customers to move from month-to-month plans to annual contracts.

2. Improve Customer Support

	Enhance support staff training and service quality to address customer dissatisfaction.

3. Review Fiber Optic Service

	Investigate why fiber optic customers have higher churn and improve service quality or pricing strategies.

4. Retain High-Risk Customers

	Develop targeted retention campaigns for:

	Senior citizens
	New customers
	High monthly charge customers

5. Monitor Competitor Offerings

	Continuously benchmark pricing, internet speed, and service packages against competitors.


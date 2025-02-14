```
Telecom Customer Churn Analysis

This project explores customer churn in the telecom industry using a dataset with 7043 observations and 21 columns. The aim is to identify key factors influencing churn and offer practical insights to help reduce churn rates.
Overview

    Customer Retention Focus: Retaining customers is more cost-effective than acquiring new ones. This project examines various factors affecting churn.
    Data-Driven Insights: Analyzes customer demographics, service usage, payment methods, and other attributes to understand churn behavior.
    Visualization & Analysis: Uses histograms, violin plots, bar charts, and interactive maps to highlight trends and patterns in the data.
    Actionable Recommendations: Provides strategies based on the analysis, such as loyalty programs, flexible payment options, and service improvements.

Data Description

The dataset includes:

    Customer Details: Unique customer IDs, demographics (e.g., gender, state, city).
    Service Information: Phone and internet service details, contract type, additional services (e.g., online security, tech support).
    Financial Data: Monthly charges, total charges, Customer Lifetime Value (CLTV).
    Churn Indicators: Churn labels, churn score, churn reason.

Key Findings

    Total Charges & Tenure: Customers who spend more and stay longer tend to have lower churn rates.
    Payment Methods & Contract Types: Customers using electronic checks and short-term contracts are more likely to churn.
    Internet Service: Fiber optic users show a higher churn rate compared to those without internet service.
    Additional Services: Lack of services like online security and tech support correlates with higher churn.
    Geographical Insights: While churn rates are similar across cities, customer counts differ significantly.

Recommendations

    Loyalty Programs: Reward long-term, high-spending customers.
    Customer Engagement: Increase personalized communication with high CLTV customers.
    Payment Options: Provide flexible payment methods to reduce churn among electronic check users.
    Contract Incentives: Encourage longer contracts through benefits or discounts.
    Service Quality: Focus on improving fiber optic service quality and promoting additional support services.
    Targeted Efforts: Concentrate retention strategies in cities with high customer counts like Los Angeles and San Diego.

How to Run

    Requirements:
    Ensure Python and the following libraries are installed:
        Pandas
        Matplotlib
        Seaborn
        Plotly
        Openpyxl (for Excel file reading)

    Data Loading:
    Place the Telco_customer_churn.xlsx file in the project folder.

    Execution:
    Run the provided notebook or scripts to load, clean, and analyze the data. The code includes data preprocessing, visualization, and detailed analysis of churn factors.

Conclusion

The analysis highlights that customer retention is crucial for telecom operators. By understanding the key drivers of churn and implementing targeted strategies, companies can reduce churn rates, improve customer satisfaction, and enhance overall profitability.

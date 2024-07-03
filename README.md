# Bank-Customer-Churn-Analysis
Customer Churn Rate Analysis Dashboard : This project provides a comprehensive guide and resources for creating a Customer Churn Rate Analysis Dashboard using Microsoft Power BI. The analysis aims to understand the factors contributing to customer churn in a bank and provides actionable insights for improving customer retention.


Data Set
The dataset includes the following columns:
customer_id: ID of the customer
credit_score: CBIL (credit score) of the customer
country: Country of the customer
gender: Gender of the customer (Male or Female)
age: Age of the customer
tenure: Number of years the customer has been with the bank
balance: Account balance
product_number: Product categorized by number
credit_card: Whether the customer has a credit card (1) or not (0)
active_member: 1 for Active customers, 0 for Inactive customers
estimated_salary: Salary of the customer
churn: Whether the customer has left the bank (1 for churned, 0 for not churned)

Data Transformation
The following steps were undertaken to transform the data for analysis:
Use first row as header: Set the first row of the dataset as the header.
Remove useless column: Removed columns that are not useful for the analysis, such as 'estimated_salary'.
Rename columns: Renamed columns for clarity in visualizations.
Prepare data types: Ensured that data types are correctly assigned for each column.
Add column from example: Created a new column for product names (e.g., Products Prod 1, Prod 2, etc.).

Replace values:
Replaced credit card status values with 'Owned' (1) or 'Not Owned' (0).
Replaced activity status values with 'Active' (1) or 'Inactive' (0).
Add conditional columns: Created new columns for Age Groups, Credit Scores, and Account Balance categories.
Create measures: In the report section, created measures for:
Number of customers (Customer)
Number of customers lost (Customer lost)
Churn rate

Data Modeling
Create Queries: Modeled the data for analysis and visualization.
Model View: Reviewed and edited relationships between tables.
Data Analysis
DAX Measures: Created measures using Data Analysis Expressions (DAX) to derive insights and metrics relevant to customer churn.

Data Visualization
Visual Elements: Selected and formatted visual elements to represent the data effectively.
Enhance Report: Used and customized themes to enhance the report's visual appeal.

Publish
Save & Publish: Saved the report and published it to Power BI Service for sharing and collaboration.
Getting Started

Conclusion
This project equips you with the skills and knowledge to create an insightful Customer Churn Rate Analysis Dashboard using Power BI. By understanding the factors contributing to customer churn, you can develop strategies to improve customer retention and drive business success.

Maven Dashboard : https://mavenanalytics.io/project/16705
LinkedIn : https://www.linkedin.com/in/codewithvermaabhishek/edit/forms/project/new/?profileFormEntryPoint=PROFILE_SECTION

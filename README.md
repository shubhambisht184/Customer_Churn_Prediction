📊 Customer Churn Analysis

An end-to-end Data Analytics project that transforms raw customer data into meaningful business insights using Excel, Python, Pandas, NumPy, MySQL, SQL, and Power BI.

📌 Project Overview

Customer retention is one of the most important challenges for subscription-based businesses. Losing customers directly affects revenue and long-term business growth. This project focuses on analyzing customer data to understand customer churn patterns, customer behavior, revenue performance, contract preferences, subscription types, payment methods, and customer tenure.

The project follows a complete end-to-end data analytics workflow, starting from a raw and unclean Excel dataset and progressing through data cleaning, preprocessing, feature engineering, database management, SQL analysis, and interactive Power BI visualization.

The main objective is to convert raw customer data into a structured and analysis-ready dataset and then use analytical techniques to generate insights that can support better customer retention and business decisions.

🎯 Project Objectives

The key objectives of this project are:

Analyze customer churn and retention patterns.
Identify customer segments with higher churn.
Understand the relationship between customer tenure and churn.
Analyze revenue and customer value.
Compare churn across different contract types.
Analyze subscription and internet service preferences.
Study payment method distribution.
Identify high-value customers.
Analyze geographical differences in churn and revenue.
Build an interactive dashboard for monitoring important business KPIs.
🔄 Complete Project Workflow
📁 Raw Excel Dataset
        ↓
🐍 Python
        ↓
🐼 Pandas & NumPy
        ↓
🧹 Data Cleaning & Preprocessing
        ↓
⚙️ Feature Engineering
        ↓
📁 Clean Dataset
        ↓
🗄️ MySQL Database
        ↓
💻 SQL Analysis
        ↓
📊 Power BI Dashboard
        ↓
💡 Business Insights
🧹 1. Data Cleaning & Preprocessing

The project starts with a raw customer churn dataset stored in Excel. The dataset contains different data quality issues such as missing values, duplicate records, inconsistent text values, extra spaces, invalid numerical values, and date formatting issues.

Python was used to clean and prepare the dataset for further analysis.

Data Cleaning Tasks
Imported the dataset using Pandas.
Performed an initial inspection using head(), info(), describe(), and shape.
Checked for missing values.
Identified and removed duplicate records.
Replaced dirty values such as N/A, NULL, blank values, and spaces with missing values.
Removed unnecessary spaces from text columns.
Standardized customer names, states, cities, subscription types, and contract types.
Standardized the Churn column into consistent Yes and No values.
Converted numerical columns into appropriate numeric data types.
Removed invalid age values outside the defined range.
Removed negative monthly and total charges.
Converted the last interaction date into a proper date format.
Filled missing values using appropriate methods.

The cleaning process converts the raw dataset into a consistent and analysis-ready format.

⚙️ 2. Feature Engineering

After cleaning the dataset, additional features were created to improve the analysis and provide deeper business insights.

📊 Features Created
Feature	Description
💰 Customer Value	Calculated using Monthly Charges × Tenure
💵 Monthly Revenue	Represents the customer's monthly charges
📅 Tenure Group	Customers grouped into different tenure ranges
👤 Senior Flag	Classifies customers as Senior or Adult
🚨 Churn Flag	Converts Churn status into numerical 1/0 values

These engineered features make it easier to analyze customer value, customer lifecycle, and churn behavior.

🗄️ 3. MySQL Database

After completing the data cleaning and feature engineering process, the cleaned dataset was exported and loaded into MySQL.

The cleaned customer data was stored in a database table named:

customer_churn

MySQL was used to provide structured storage and allow SQL-based business analysis on the cleaned dataset.

💻 4. SQL Analysis

SQL was used to analyze the cleaned customer data and answer important business questions.

🔍 Analysis Performed
Total number of customers
Total churned customers
Overall churn rate
Average monthly charges
Average customer tenure
Churn by contract type
Customers by internet service
Churn by state
Customers by payment method
Customers by subscription type
Revenue by state
Average charges by contract type
Senior citizen churn
Top 10 high-value customers
Customers without technical support

These queries help transform the cleaned dataset into useful business information and identify important customer and revenue patterns.

📊 5. Power BI Dashboard

The analyzed data was then visualized using Microsoft Power BI.

An interactive dashboard was created to provide a centralized view of customer churn, retention, revenue, and customer characteristics.

📌 KPI Cards

The dashboard includes important KPIs such as:

👥 Total Customers
🚨 Churn Customers
✅ Retained Customers
📉 Churn Rate
💰 Total Revenue
💵 Average Monthly Charges
📅 Average Tenure
📈 Dashboard Visualizations

The dashboard contains:

Churn by Contract Type
Churn by Subscription Type
Churn by State
Revenue by State
Internet Service Distribution
Payment Method Distribution
Senior Citizen vs Churn
Tenure Group vs Churn
Customer Value by Subscription
🎛️ Interactive Slicers

Users can dynamically filter the dashboard using:

State
City
Contract Type
Subscription Type
Internet Service
Payment Method
Senior Citizen
Churn
Tenure Group
Last Interaction Date

This allows users to explore customer behavior and churn patterns across different segments.

💡 Business Insights

The project is designed to help businesses understand their customer base and make data-driven decisions.

The analysis can help stakeholders:

Identify customer groups with higher churn.
Monitor overall churn and retention.
Understand customer tenure patterns.
Compare different contract and subscription types.
Analyze revenue generated across states.
Identify high-value customers.
Understand payment method preferences.
Analyze the relationship between technical support and customer churn.
Evaluate the revenue impact associated with customer behavior.
Develop better customer retention strategies.
🛠️ Technology Stack
Technology	Usage
📗 Excel	Raw data source
🐍 Python	Data cleaning and preprocessing
🐼 Pandas	Data manipulation
🔢 NumPy	Numerical operations
🗄️ MySQL	Database storage
💻 SQL	Data analysis
📊 Power BI	Dashboard and visualization
📂 Project Structure
Customer-Churn-Analysis/
│
├── 📁 Dataset/
│   └── Churn_Unclean_Project.xlsx
│
├── 📁 Python/
│   └── Data_Cleaning.ipynb
│
├── 📁 SQL/
│   └── Churn_Analysis.sql
│
├── 📁 PowerBI/
│   └── Customer_Churn_Dashboard.pbix
│
├── 📁 Cleaned_Data/
│   └── Clean_Churn_Data.xlsx
│
└── 📄 README.md
🎓 Skills Demonstrated

Through this project, the following practical Data Analytics skills were demonstrated:

Data Cleaning
Data Preprocessing
Data Transformation
Feature Engineering
Exploratory Data Analysis
SQL Analysis
MySQL Database Management
Business Intelligence
Power BI Dashboard Development
Data Visualization
Business Insight Generation

📈 Project Outcome

This project demonstrates a complete real-world Data Analytics workflow, from collecting and cleaning raw customer data to performing SQL analysis and building an interactive Power BI dashboard.

The final solution provides a structured way to analyze customer churn, retention, revenue, customer value, tenure, contracts, subscriptions, payment methods, and geographic patterns.

By combining Python for data preparation, MySQL and SQL for analysis, and Power BI for visualization, the project converts raw customer information into an interactive analytical solution that can support data-driven business and customer retention decisions.

⭐ Conclusion

The Customer Churn Analysis project showcases how different Data Analytics tools can be integrated into a single end-to-end workflow. It demonstrates practical experience in Python, Pandas, SQL, MySQL, Excel, and Power BI, while focusing on a real-world business problem: understanding and reducing customer churn.

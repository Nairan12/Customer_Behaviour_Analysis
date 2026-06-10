# Customer_Behaviour_Analysis
Customer shopping behavior analysis project featuring data cleaning with pandas, PostgreSQL integration, SQL analytics, and an interactive Power BI dashboard for actionable business insights.


# Customer Shopping Behaviour Analysis

## Overview
This project analyzes customer shopping behaviour using Python, PostgreSQL, SQL, and Power BI. It follows an end-to-end analytics workflow, from data cleaning and feature engineering to database integration, SQL analysis, and interactive dashboard creation.

## Dataset
The dataset contains customer transaction and demographic information, including:
- Customer demographics (age, gender)
- Product categories and items purchased
- Purchase amounts
- Review ratings
- Discounts and subscription status
- Shipping types and purchase frequency

## Workflow
1. Cleaned and preprocessed the data using Pandas.
2. Handled missing values and standardized column names.
3. Performed feature engineering by creating age groups and numerical purchase frequency variables.
4. Loaded the cleaned data into PostgreSQL.
5. Wrote SQL queries to answer business questions and generate insights.
6. Built an interactive Power BI dashboard for visualization.

## Dashboard
The Power BI dashboard includes:
- KPI cards for key business metrics
- Revenue analysis by customer segments
- Product and category performance
- Customer demographics and purchasing behaviour
- Interactive filters for dynamic exploration

> **Dashboard Preview**
>
> <img width="1222" height="730" alt="dashboard" src="https://github.com/user-attachments/assets/3f8cbb53-74fd-4c40-aa90-f458cfb05252" />

>
> `![Dashboard](images/dashboard.png)`

## Key Results
- Compared revenue across customer segments.
- Identified top-performing products based on review ratings.
- Analyzed subscriber and non-subscriber spending patterns.
- Evaluated discount usage and purchase behaviour.
- Segmented customers based on previous purchase history.
- Examined revenue contribution across different age groups.

## How to Run
1. Clone this repository.
2. Install the required Python libraries.
3. Run the Jupyter notebook to perform data cleaning and preprocessing.
4. Load the processed data into PostgreSQL.
5. Execute the SQL queries for analysis.
6. Open the Power BI (`.pbix`) file to explore the interactive dashboard.

## Technologies Used
- Python (Pandas)
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

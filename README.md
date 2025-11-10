Customer Shopping Behavior Analysis
Overview

This project focuses on understanding customer shopping behavior using real-world transactional data. The main goal is to analyze how customers spend, what products they prefer, and how their buying patterns vary.
The project includes data loading, cleaning, exploration, SQL querying, dashboard creation in Power BI, and preparing a final report and presentation.

Dataset

File name: customer_shopping_behavior.csv

Records: 3,900

Columns: 18 attributes related to customers, products, and transactions

Data used for: identifying spending patterns, preferred categories, and subscription behavior

Tools and Technologies

Python: pandas, NumPy, matplotlib, seaborn

Database: PostgreSQL / MySQL / SQL Server

Visualization: Power BI

Reporting: PDF or Word report

Presentation: Gamma App

Development environment: Jupyter Notebook

Project Steps
1. Data Loading

The dataset was imported into Python using pandas for initial checks and inspection.

2. Data Cleaning

Treated 37 missing values

Removed duplicates and corrected data types

Created new calculated fields for better analysis

3. Exploratory Data Analysis (EDA)

Explored customer segments, product categories, and purchase frequency using summary statistics and visualizations.
Key charts include spending distribution, top product categories, and customer segment analysis.

4. SQL Queries

The cleaned dataset was imported into PostgreSQL/MySQL/SQL Server to run analytical queries such as:

Total and average spending per customer

Category-wise sales performance

Customer segmentation by frequency and value

5. Power BI Dashboard

An interactive dashboard was created to visualize:

Overall sales trends

Top customers and products

Monthly and category-wise revenue

Subscription and spending insights

6. Report and Presentation

A final analytical report was prepared summarizing findings and insights.
A concise presentation was created using Gamma to visually communicate the results.

Key Insights

A small group of high-value customers contributed to a major share of total sales.

Electronics and fashion were the most purchased categories.

Weekend transactions and recurring subscription users showed higher spending.

The analysis provides a base for customer retention and targeted marketing strategies.

How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis


Install required libraries:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook


Open and execute the notebook file customer_behavior_analysis.ipynb step by step.

Run SQL scripts:
Import the dataset into your SQL environment and execute queries from the provided SQL file.

View the Dashboard:
Open the .pbix file in Power BI Desktop to explore interactive visuals.

View the Report and Presentation:

Final Report: /reports/final_report.pdf

Presentation: /presentations/final_presentation_gamma.pdf

Future Scope

Automate data updates directly from the SQL database to Power BI

Add machine learning models for customer segmentation and churn prediction

Integrate dashboard insights into a web-based application

Author

Bhagyashree Shet
📧 bhagyashet888@gmail.com
LinkedIn:[www.linkedin.com/in/bhagya-shet](https://www.linkedin.com/in/bhagya-shet/)

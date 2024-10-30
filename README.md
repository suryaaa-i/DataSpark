# DataSpark
DataSpark: Illuminating Insights for Global Electronics
Problem Statement
As part of Global Electronics' data analytics team, the aim is to perform a thorough Exploratory Data Analysis (EDA) to uncover actionable insights for enhancing customer satisfaction, optimizing operations, and driving business growth. Global Electronics, a top retailer in consumer electronics, has shared datasets covering customers, products, sales, stores, and exchange rates. By leveraging this data, our goal is to understand the business deeply and highlight areas for potential improvement.

Business Use Cases
Our analysis will empower Global Electronics to:

Enhance marketing strategies: Identify target demographics and tailor marketing campaigns.
Optimize inventory management: Pinpoint product popularity and seasonal trends.
Improve sales forecasting: Recognize demand patterns and adjust inventory.
International pricing strategies: Incorporate currency trends for pricing alignment.
Collectively, these insights will help boost customer satisfaction and business growth.

Data and Tools Used
Tools Used:

IDE: Jupyter Notebook, PyCharm
Libraries: Python, Pandas, Matplotlib, Seaborn
Database: SQLite3
Visualization: Power BI
Data Sources:

Kaggle: Global Electronics Retailers
Dataset Overview:

Customer data (customers.csv): Includes demographic information like gender, D.O.B, city, etc.
Sales data (sales.csv): Transaction details like order number, date, quantity, and store location.
Products data (products.csv): Product details including name, category, unit cost, and price.
Stores data (stores.csv): Information on store location, square footage, and opening date.
Exchange rates (exchangerates.csv): Currency exchange data for global sales analysis.
Approach
1. Data Cleaning and Preparation
Address missing values, convert date and numerical fields, and merge related tables for analysis.
2. Loading Data into SQLite3
Store each dataset in an SQLite3 database as separate tables for structured querying and efficient data handling.
3. Power BI Visualization
Connect SQLite3 to Power BI and import tables to create interactive dashboards.
4. SQL Queries for Insights
Write and execute SQL queries to uncover patterns and trends across various domains: customer behavior, sales, product performance, and store analysis.
Analysis Workflow and Key Insights
Customer Analysis
Demographics: Distribution across gender, age, and location.
Purchase Patterns: Average order value, purchase frequency, and product preferences.
Segmentation: Customer groups by demographics and behavior to target marketing efforts.
Sales Analysis
Sales Trends: Overall performance, seasonality, and trend analysis.
Product Performance: Revenue and quantity sold across products.
Store Contribution: Sales by store and region.
Currency Impact: Impact of exchange rates on sales.
Product Analysis
Popularity and Profitability: Top-performing products and profit margins.
Category Analysis: Sales across categories and subcategories.
Store Analysis
Store Performance: Sales trends, store size, and operational data analysis.
Geographical Insights: Regional high-performing areas.
Key Findings
Demographic Insights:

Country: The U.S. leads in customer numbers, followed by notable interest from Canada and Germany.
Cities: Toronto, Montreal, and Calgary are top Canadian cities.
Age: Majority are aged 60+, showing engagement from an older demographic.
Sales and Customer Engagement:

Customers with No Orders: 3,379 customers represent a missed revenue potential of $15M, warranting targeted campaigns.
Frequency of Visits: Visits cluster between 5-10; this segmentation can refine campaign strategies.
Currency and Regional Trends:

Currency: Most sales occur in USD, EUR, and GBP, highlighting international reach.
Exchange Rates: Minimal effect of AUD, CAD, EUR, and GBP rates on USD revenue indicates stable international pricing.
Product Insights:

Category Performance: Computers dominate with 41.75% of orders and $19M in revenue.
Top Products: WWI Desktop PC.33 X2330 Black leads with 550 units sold.
Store Analysis:

Top Store: The online store generates 20.45% of total sales, indicating a strong digital presence.
Store Age and Size: No correlation with revenue, though 9 stores show no sales.
Temporal Analysis:

Revenue Trends: Sales rose from 2016-2019, declined in 2020 (likely due to COVID-19), and remained challenging in early 2021.
Seasonality: Top sales months are December, January, and February, with April being the lowest.
Next Steps and Recommendations
Marketing Campaigns:

Develop campaigns targeting customers aged 60+ and underrepresented cities.
Engage the 3,379 customers with no orders for potential $15M in revenue.
Store Optimization:

Evaluate the 9 stores with no orders for closure or repurposing, as the online store shows strong performance.
Pricing Strategy:

Currency stability allows for consistent pricing, but consider adjusting for regions with higher USD equivalence.
Product Strategy:

Focus on popular categories like computers and leading products like the WWI Desktop PC for promotions.
This streamlined setup allows stakeholders to quickly identify critical insights while leveraging SQLite for flexible, efficient data management and Power BI for interactive reporting.

POWERBI VISUALIZATION:
![DataSpark](https://github.com/user-attachments/assets/3eaafa56-e290-4efa-86e3-216178a99cc5)
![Customer Performance](https://github.com/user-attachments/assets/d492bc0d-7ec0-4b9c-9af5-11ed8f69d4d2)
![Yearly performance](https://github.com/user-attachments/assets/83595770-1b1b-4ac5-bc25-5bb1ff57056a)
![Store Performance](https://github.com/user-attachments/assets/2dac8cec-e3df-4d50-ab65-62d7def616c7)
![Product Performance](https://github.com/user-attachments/assets/49f14501-7538-405f-a589-9ec0bc593a2f)

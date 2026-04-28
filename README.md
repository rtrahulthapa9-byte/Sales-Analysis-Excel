# Sales-Analysis-Excel

![Dashboard Screenshot](dashboard.png)
About datasets
Data consists of Amazon sales from 2025. I imported a messy dataset from Kaggle, which contains 14 columns, including Order ID, Date, Customer ID, Product Category, Product Name, Quantity, Unit Price, Total Sales Price, Payment Method, Delivery Status, Review Rating, Review Text, State, and Country.

Data cleaning 
I used Power Query in Excel to clean the data by applying TRIM and formatting for consistency, removing duplicates, and standardizing the Date column. I handled missing values by calculating Unit Price as Total Sales ÷ Quantity, and replaced blank Customer IDs with “Guest_User” while keeping those records for analysis.

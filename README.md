# Customer Shopping Trends Analysis — SQL, Python & Power BI

An end-to-end data analytics project analyzing customer shopping trends from retail data. The workflow covers data cleaning and exploration in Python, business-question analysis in SQL, and an interactive dashboard built in Power BI.

## Project Overview

The goal of this project is to take raw retail customer data and turn it into actionable business insights — identifying customer segments, purchase drivers, and loyalty patterns that a retail business could use to make decisions.

The workflow follows a typical analyst pipeline:

1. **Data Preparation & EDA (Python)** — Import the raw dataset, clean it, and explore it for patterns before loading it into a SQL database.
2. **Data Analysis (SQL)** — Query the database to answer specific business questions about customer segments, loyalty, and what drives purchases.
3. **Visualization (Power BI)** — Build an interactive dashboard that surfaces the key trends and patterns for stakeholders.

## Tech Stack

- **Python** (pandas, Jupyter Notebook) — data cleaning and exploratory analysis
- **SQL** — business-question queries against the cleaned dataset
- **Power BI** — interactive dashboard and visualization

## Project Structure

```
├── customer_shopping_behavior.csv          # Raw dataset
├── Customer_Shopping_Behavior_Analysis.ipynb   # Data cleaning + EDA (Python)
├── customer_behavior_sql_queries.sql       # SQL queries answering business questions
├── customer_behavior_dashboard.pbix        # Power BI dashboard
└── README.md
```

## How to Run This Project

1. Clone the repository
   ```
   git clone [<your-repo-url>](https://github.com/akilajayarathna/Customer-Shopping-Trends-Analysis-SQL-Python-Power-BI.git)
   cd Customer-Shopping-Trends-Analysis-SQL-Python-Power-BI
   ```
2. Open `Customer_Shopping_Behavior_Analysis.ipynb` and run through the data import, cleaning, and exploration steps.
3. Load the cleaned data into a SQL database (MySQL/PostgreSQL/MS SQL Server).
4. Run the queries in `customer_behavior_sql_queries.sql` to answer the business questions.
5. Open `customer_behavior_dashboard.pbix` in Power BI to explore the interactive dashboard.

## Key Insights

- Customer base of ~3.9K customers, with an average purchase amount of $59.76 and an average review rating of 3.75/5.
- Only 27% of customers are subscribed, while 73% are non-subscribers — indicating a large opportunity to convert one-time buyers into subscribers.
- Clothing is the top-performing category by both revenue and sales volume, followed by Accessories, Footwear, and Outerwear (lowest).
- Young Adults generate the highest revenue and sales among all age groups, followed by Middle-aged customers, while Seniors and Adults contribute the least.
- Revenue and sales trends are consistent across categories and age groups, suggesting Clothing and the Young Adult segment should be prioritized in marketing and inventory decisions.

## Dashboard Preview

<img width="1159" height="617" alt="Dashboard" src="https://github.com/user-attachments/assets/d0ca6a99-bc50-4348-a7c6-61f5d4100354" />


## What I Learned

- How to move data through a full analytics pipeline — cleaning and exploring it in Python, loading it into a SQL database, writing business-focused SQL queries, and visualizing the results in Power BI.
- How to design a dashboard that communicates KPIs (customer count, average purchase, average rating) alongside breakdowns by category and age group, using interactive filters like subscription status, gender, and shipping type.
- How to translate raw query results into business-relevant insights rather than just presenting numbers.

## Credits

This project was built by following a tutorial by [Amlan Mohanty](https://www.youtube.com/@amlanmohanty1) to learn the end-to-end SQL + Python + Power BI analytics workflow. The dataset and project structure are based on his [original project](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI) (MIT licensed). Analysis, queries, and dashboard were built and run by me as a learning exercise.

## License

MIT

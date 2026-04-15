# Customer Shopping Behavior Analysis: Python-SQL-Power BI

This project analyzes 3,900 transactions to uncover patterns in customer spending, demographics, and subscription behavior Using Python for cleaning, MySQL Workbench for querying, and Power BI for visualization, I identified that male customers and young adults are the primary revenue driversThe analysis provides data-driven recommendations to optimize loyalty programs and boost subscription rates.

### Tools & Technologies

  * **Python**: Pandas (Data cleaning and preprocessing)
  * **SQL**: MySQL Workbench (Business logic and aggregation) 
  * **Power BI**: Interactive dashboarding

### Dataset

  * **Source**: Customer Shopping Behavior Dataset 
  * **Size**: 3,900 rows, 18 columns 
  * **Description**: Contains customer demographics, purchase details (category, amount, item), and behavioral data (subscription status, review ratings).

###  Project Workflow

1.  **Data Cleaning**: Imputed 37 missing values in `Review Rating` using category-specific medians
2.  **Feature Engineering**: Created `age_group` bins and standardized column names to snake_case
3.  **SQL Queries**: Migrated cleaned data to MySQL Workbench to analyze revenue by gender, age, and shipping type
4.  **EDA**: Explored customer segments (Loyal, Returning, New) and discount-dependent products
5.  **Visualization**: Developed a Power BI dashboard to track KPIs like average purchase amount ($59.76) and review ratings (3.75)

###  Key Insights

  * **Revenue Drivers**: Male customers generated significantly more revenue ($157,890) than female customers ($75,191)
  * **Top Segment**: **Young Adults** are the highest revenue contributors, totaling $62,143
  * **Subscription Status**: Only **27%** of customers are subscribers, even though average spend is nearly identical across both groups (\~$59)
  * **Product Performance**: **Clothing** is the dominant category for sales; **Gloves** and **Sandals** are the highest-rated items.
  * **Customer Loyalty**: Identified **3,116 Loyal customers**, forming the core of the business

###  Visualizations

<img width="1349" height="737" alt="Dasboard" src="https://github.com/user-attachments/assets/2697aa7c-85bd-4de1-a685-f719199b7ca4" />


###  Author

  * **Name**: Niyasudheen AM
  * **LinkedIn**: https://www.linkedin.com/in/niyasudheenam/
  * **Gmail**: amniyas380@gmail.com

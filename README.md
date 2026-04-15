# Customer Shopping Behavior Analysis: Python-SQL-Power BI

[cite_start]This project analyzes 3,900 transactions to uncover patterns in customer spending, demographics, and subscription behavior[cite: 3, 6]. [cite_start]Using Python for cleaning, PostgreSQL for querying, and Power BI for visualization, I identified that male customers and young adults are the primary revenue drivers[cite: 36, 37, 60, 65, 66]. [cite_start]The analysis provides data-driven recommendations to optimize loyalty programs and boost subscription rates[cite: 115, 118].

### 🧰 Tools & Technologies

  * [cite_start]**Python**: Pandas (Data cleaning and preprocessing) [cite: 14, 15]
  * [cite_start]**SQL**: MySQL Workbench (Business logic and aggregation) [cite: 25, 27]
  * [cite_start]**Power BI**: Interactive dashboarding [cite: 76, 77]

### 📂 Dataset

  * [cite_start]**Source**: Customer Shopping Behavior Dataset [cite: 1]
  * [cite_start]**Size**: 3,900 rows, 18 columns [cite: 6, 7]
  * [cite_start]**Description**: Contains customer demographics, purchase details (category, amount, item), and behavioral data (subscription status, review ratings)[cite: 9, 10, 11].

### 🔍 Project Workflow

1.  [cite_start]**Data Cleaning**: Imputed 37 missing values in `Review Rating` using category-specific medians[cite: 12, 19].
2.  [cite_start]**Feature Engineering**: Created `age_group` bins and standardized column names to snake\_case[cite: 20, 22].
3.  [cite_start]**SQL Queries**: Migrated cleaned data to MySQL Workbench to analyze revenue by gender, age, and shipping type[cite: 25, 28, 44, 60].
4.  [cite_start]**EDA**: Explored customer segments (Loyal, Returning, New) and discount-dependent products[cite: 50, 53].
5.  [cite_start]**Visualization**: Developed a Power BI dashboard to track KPIs like average purchase amount ($59.76) and review ratings (3.75)[cite: 81, 84, 86].

### 📊 Key Insights

  * [cite_start]**Revenue Drivers**: Male customers generated significantly more revenue ($157,890) than female customers ($75,191)[cite: 34, 37].
  * [cite_start]**Top Segment**: **Young Adults** are the highest revenue contributors, totaling $62,143[cite: 65, 66].
  * [cite_start]**Subscription Status**: Only **27%** of customers are subscribers, even though average spend is nearly identical across both groups (\~$59)[cite: 49, 94].
  * **Product Performance**: **Clothing** is the dominant category for sales; [cite_start]**Gloves** and **Sandals** are the highest-rated items[cite: 43, 111].
  * [cite_start]**Customer Loyalty**: Identified **3,116 Loyal customers**, forming the core of the business[cite: 54].

### 📈 Visualizations

<img width="1349" height="737" alt="Dasboard" src="https://github.com/user-attachments/assets/2697aa7c-85bd-4de1-a685-f719199b7ca4" />


### 👤 Author

  * **Name**: Niyasudheen AM
  * **LinkedIn**: https://www.linkedin.com/in/niyasudheenam/
  * **Gmail**: amniyas380@gmail.com

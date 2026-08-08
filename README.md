# Himanshu Singh - Data Analyst Portfolio

## About
Warm Greetings, I am Himanshu, a 3rd year BCA student specialising in Data Analytics. I have been focusing on creating meaningful Data Analyst projects based on real world problems and real world data. Day by day, I am derived to hone my professional skillset of technical tools and critical thinking. I am excited to bring my technical and analytical skills to the field of data analytics as an entry-level Data Analyst.

My Resume in pdf.

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Portfolio Projects
 In this section I will list data analytics projects briefly and give a concise walkthrough. 
 For detailed information about any specific project, please refer to the full project folder link.

### 1) E-Commerce Churn & Retention Analysis (End-To-End)

**Goal:** To identify customers at risk of churn, understand why they leave, and prioritize retention strategies based on customer value.

**Code:** 
- [`1_DDL.sql`](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/%5BEnd-To-End%5D%20E-Commerce%20Churn%20%26%20Retention%20Analysis/Deliverables/1_DDL.sql)
- [`2_ETL.sql`](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/%5BEnd-To-End%5D%20E-Commerce%20Churn%20%26%20Retention%20Analysis/Deliverables/2_ETL.sql)
- [`3_DATA_QUALITY.sql`](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/%5BEnd-To-End%5D%20E-Commerce%20Churn%20%26%20Retention%20Analysis/Deliverables/3_DATA_QUALITY.sql)
- [`4_ANALYTICS.sql`](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/%5BEnd-To-End%5D%20E-Commerce%20Churn%20%26%20Retention%20Analysis/Deliverables/4_ANALYTICS.sql)
- [`run_all.sql`](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/%5BEnd-To-End%5D%20E-Commerce%20Churn%20%26%20Retention%20Analysis/Deliverables/run_all.sql)

**Description:** This project builds an end-to-end analytics pipeline for customer churn analysis using the Brazilian Olist e-commerce dataset. The objective was to design a production-style analytical solution that enables marketing teams to identify customers at risk of churn, understand why they leave, and prioritize retention strategies based on customer value.

**Skills:** Data Warehousing, Star Schema, Data Pipeline, Automated ETL, SQL Analysis, Data Visualisation

**Technology:** PostgreSQL, DBeaver, Tableau, Excel

**Results:** 
- Delivery delay is the strongest observed churn driver, where churned customers wait an average of 12.69 days (2x of Active Customers) while Active customers wait 6.58 days.
- Average Month 1 retention is only 5.22% and falls below 1% from Month 2 onward, signaling a need of swift retention strategies.
- Business Recommendations in [2‑page insights report](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/%5BEnd-To-End%5D%20E-Commerce%20Churn%20%26%20Retention%20Analysis/Deliverables/Insights%20Report.pdf) with 4 data‑backed, *actionable recommendations*, proving ability to translate data into business strategy along with an [Executive Dashboard](https://public.tableau.com/app/profile/himanshu.singh3621/viz/E-CommeceChurnRetentionAnalysis/Executive_Churn_Dashboard?publish=yes)

### 2) California Hospital Labor Market & Workforce Risk Analysis (API) 

**Goal:** To identify which geographic markets show signs of a *breaking point* in the hospital sector (rising costs alongside a shrinking workforce) that may indicate future facility closures or service reductions?

**Code:** [California Hospital Labor Market & Workforce Risk Analysis (API).ipynb](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/.%5BAPI%5D%20Hospital%20Wages%20%26%20Employment%20Trend%20Analysis%20%5B2020-2025%5D/notebook/Final_Notebook.ipynb)

**Description:** This project analyzes county-level hospital labor trends to address a real business problem in the U.S. healthcare sector. Californian counties are facing rising hospital labor costs, healthcare workforce shortages, and changing labor market conditions. Based on Bureau of Labor Statistics (BLS) and Quarterly Census of Employment and Wages (QCEW) data, this project identifies geographic markets that show signs of a breaking point in the hospital sector (rising costs alongside a shrinking workforce) that may indicate future facility closures or service reductions.


**Skills:** API requests, Data Cleaning, Exploratory Data Analysis, Data Visualisation

**Technology:**  Python, Pandas, Matplotlib, Seaborn, Excel, Tableau

**Results:**
- From year 2020 to 2025, Alameda County faced **decrease of 8%** in employment levels, and **29.9% increase** in average weekly wage growth, showing signs of breaking point in the hospital sector... (rising costs + shrinking workforce).
- Facilitated [Insights Report with actionable recommendations](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/.%5BAPI%5D%20Hospital%20Wages%20%26%20Employment%20Trend%20Analysis%20%5B2020-2025%5D/Insight_Report/Insights%20Report.pdf) for the concerned authorities.
- Prepared an [Executive Dashboard](https://public.tableau.com/app/profile/himanshu.singh3621/viz/Book1_17837645877920/Dashboard1?publish=yes).

### 3) Iowa Corn Margin Stress Analysis (API) 

 **Goal:** To identify which Iowa counties are under the most financial pressure by combining live USDA yield data with cost of production estimates.

**Code:** [Iowa Corn Margin Stress Analysis (API).ipynb](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/.%5BLIVE%20API%5D%20Iowa%20Corn%20Margins%3A%20Real%E2%80%91Time%20USDA%20Data%20Analysis%20(2015%E2%80%932025)/Live%20API%20Agriculture%20DA%20Project/NOTEBOOK.ipynb)

**Description:** US corn farmers are facing a severe margin squeeze. Production costs remain high while commodity prices fluctuate, leaving many operations financially vulnerable. This project identifies which Iowa counties are under the most financial pressure by combining live USDA yield data with cost of production estimates. The final output is a county‑level ranking of estimated profit margins, highlighting the regions at greatest risk.

**Skills:** API requests, Data Cleaning, Exploratory Data Analysis, Data Visualisation

**Technology:** Python, Pandas, Requests, Matplotlib, Excel

**Results:**
- According to the analysis, Corn farming in the US is a risky business in 2026.
- In the past 3 years, Iowa counties experienced a 147.6% decline in average corn profit margin, falling from $267/acre to -$127/acre.
- A $395/acre reversal that has put every county in the red
- Historically, 2021 and 2022 had $222-$267 average margin per acre, but 2025 shows a severse downturn across all counties.
- [Insight Report](https://github.com/himanshuds2025/Data-Analyst-Project/blob/main/.%5BLIVE%20API%5D%20Iowa%20Corn%20Margins%3A%20Real%E2%80%91Time%20USDA%20Data%20Analysis%20(2015%E2%80%932025)/Live%20API%20Agriculture%20DA%20Project/Insight%20Report.pdf)

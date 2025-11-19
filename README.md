**GoExplore – Revenue Analysis (2015–2017)**
**Summary**

This project analyzes GoExplore revenue performance between January 2015 and December 2017, using Google Sheets, BigQuery (SQL), and Looker Studio to transform, analyze, and visualize business data.

The goal was to evaluate sales, revenue, profit, and product performance across 21 countries  and to deliver actionable insights for strategic decision making, using only Google cloud based tools.

**Key findings include:**

€966 million total revenue

€406 million total profit (42% margin)

15 million items sold via 118,951 retailers

Eyewear (45%) as the top-selling product category

Steady growth in web-based sales and overall profitability

This project demonstrates end-to-end data handling,  from data preparation in Google Sheets, to analysis in BigQuery using SQL, and interactive dashboard creation in Looker Studio.
[DASHBOARD/LINK](https://lookerstudio.google.com/s/th5pj74tVHY "DASHBOARD/LINK")

** Languages and Tools Used**

Core Tools:

🧮 Google Sheets – data cleaning, transformation, and initial aggregation

💾 Google BigQuery – SQL-based querying, joining, and summarizing large datasets

📊 Looker Studio – visualization and dashboard creation

📈 Pivot Tables & Charts – quick analysis and insight discovery in Sheets

Query Language:

SQL (used within BigQuery for data aggregation and transformation)

**Key Learnings**

Strengthened understanding of the Google Data Stack workflow (Sheets → BigQuery → Looker Studio).

Improved SQL proficiency, including aggregations, joins, filtering, and window functions for revenue and profit analysis.

Learned how to structure data models in BigQuery for smooth connection to Looker Studio.

Practiced transforming complex data into executive level visual insights (e.g., KPIs, profit margins, category shares, and country breakdowns).

Gained experience in data storytelling , communicating technical insights to a non-technical audience (CEOs, stakeholders, etc.).

**Challenges /Overcame**

Data Cleaning in Google Sheets:
The dataset had inconsistent date formats and missing profit fields.
✅ Solution: Used Sheets formulas (ARRAYFORMULA, IFERROR, TRIM, SPLIT, QUERY) to clean and standardize data before loading into BigQuery.

Query Optimization in BigQuery:
Some SQL queries initially took too long or returned incorrect aggregations.
✅ Solution: Broke queries into smaller subqueries and used GROUP BY with SAFE_DIVIDE() to prevent errors.

Looker Studio Visualization Setup:
Configuring correct joins and metrics (e.g., revenue per category) was tricky.
✅ Solution: Verified relationships in BigQuery and used calculated fields directly in Looker Studio.

Data-to-Insight Communication:
Needed to present findings clearly to non-technical stakeholders.
✅ Solution: Focused on clear visuals (e.g., revenue per country treemap, category breakdown donut chart) and concise executive summaries.

**Additional Reflections**

This project helped me see the power of Googles integrated data tools for end-to-end analysis without external software.
It showcased my ability to:

Work with real business datasets using only Google Sheets and SQL

Build interactive dashboards that communicate value clearly

Combine technical querying skills with data storytelling for decision-making

Future improvements could include:

Automating data refresh from Sheets → BigQuery → Looker Studio

Adding forecasting SQL models for predictive insights

Expanding Looker Studio interactivity (filters, drilldowns, etc.)

**Key Insights Summary**

Area	Key Finding	Recommendation
Revenue & Profit	€966M revenue, €406M profit (42% margin)	Maintain cost efficiency, explore new revenue streams
Product Category	Eyewear = 45% of sales	Continue investing in Eyewear, diversify other products
Sales Channels	Web dominates, rising trend	Increase investment in digital marketing
Markets	US & UK top performers	Expand presence in emerging regions (China, Mexico, Singapore)

# **🚀 Business Dashboard |Maven Analytics |Sales CRM Data Challenge**


[🎥Explanation video](https://www.youtube.com/watch?v=LybwfLsCH8U)


## Problem Overview
This Power BI dashboard project was designed for Company, a global company experiencing rapid growth. As their operations scaled, so did the complexity of their data, leading to heavy reliance on Excel, which hindered efficiency and decision-making. This project resolves these issues by transforming Company’s reporting ecosystem into a dynamic, real-time analytical solution using Power BI.

## Problem Statement
Company faced operational bottlenecks due to fragmented data stored in spreadsheets. The lack of real-time analytics led to missed business opportunities, especially in fast-moving markets. Leadership had no unified visibility across departments like Sales, Market Reach, and Account Performance. Thus, a centralized, scalable reporting solution was necessary to unlock actionable insights.

## Objectives
Replace Excel-based reports with an interactive Power BI dashboard.
Enable end-to-end visibility into sales, products, market sectors, regions, and team performance.
Provide stakeholders with real-time, self-service BI capability.
Improve operational decision-making through intelligent KPIs and visualizations.

## Key Features & Dashboard Views
### 1. Sales Overview
<img width="889" height="494" alt="Capture1" src="https://github.com/user-attachments/assets/2129c1a8-a6fe-4d56-8b99-bbcc19ce9704" />

Tracks key KPIs: Total Revenue, Success Rate (63.2%), Total Opportunities, Avg. Cycle Days.
Time series analysis on revenue and opportunities.
Top-performing products (GTX Pro - $3.5M) and sectors (Retail - $1.86M).
Success rates by product and quarter.
Sales manager leaderboard (Melvin Marxen - $2.2M).

### 2. Products Dashboard
<img width="889" height="494" alt="Capture1" src="https://github.com/user-attachments/assets/cfee1dc1-9e2e-4409-9857-bb5b4af415bc" />

Product-wise breakdown: Revenue, Cycle Days, and Success Rate.
Top selling: GTX Pro ($35M) | Top winning: GTX Basic (915 deals).
Fastest sales cycle: GTX 500 (54 days).
Suggested vs Actual Price comparison with deviation indicators.

### 3. Market Reach
<img width="880" height="489" alt="Capture3" src="https://github.com/user-attachments/assets/7748f9ae-4280-40b4-8547-a3ae3ec0d44d" />

Geographic and sectoral expansion metrics.
Revenue analysis by account, sector, and country.
Revenue vs Won Opportunity comparison across sectors.
Active opportunities by type (Engaging, Lost, Prospecting).
10 sectors & 15 countries captured.

### 4. Account-wise Analysis
<img width="882" height="491" alt="Capture4" src="https://github.com/user-attachments/assets/a27aa247-a9fd-41a9-97fa-350f34ab4a0a" />

Detailed breakdown of opportunities by individual accounts.
Map visualization shows Company’s international footprint.
Sector-account level KPIs: Success Rate, QOQ Sales, and Cycle Time.
Top Revenue-Contributing Accounts: Betasoln (GTX Pro - $43K), Bubba Gump, Hatfan.

### 5. Sales Teams Performance
<img width="889" height="490" alt="Capture5" src="https://github.com/user-attachments/assets/f89e347f-3f78-4893-b643-85e3f95de3b6" />

Leaderboards for Managers and Sales Agents.
Top performer: Darcel Schlecht - $11.5M, 349 deals (11.53% share).
Sales breakdown: Regional Office, Office Manager, Sales Agent.
Performance metrics include sales, deals, success rate, and sales cycle.

### 6. Office & Regional Performance
<img width="819" height="290" alt="Capture6" src="https://github.com/user-attachments/assets/ede0562d-9eee-4d30-9553-79c0a090d262" />
<img width="816" height="287" alt="Capture7" src="https://github.com/user-attachments/assets/75453d01-d77c-4c56-8860-702753e33f88" />

Visual breakdown of office managers’ opportunity types and deal counts.
Central, West, and East office sales shown with success rates and cycle averages.
Central: $3.3M (35.4%) | West: $3.6M (37.5%) | East: $3.1M (30.9%).

## Implementation Steps
1. Database Setup
Built on star schema with clean relationship modeling.
Central fact tables connected to dimension tables (e.g., date, product, region).

2. Data Extraction & ETL
Data sourced from MySQL, Excel, and CSV files.
Used SQL + Python for ETL pipeline and data transformation.
Cleaned, standardized, and validated data for modeling in Power BI.

3. Data Modeling
Developed 10+ interlinked tables using Power BI’s model view.
Created DAX measures for KPIs like Revenue, Margin %, Cycle Time, Win Rate, etc.

4. Visualization
Created interactive dashboards using bookmarks, slicers, filters.
Integrated KPI indicators, bar charts, maps, donut charts, and stacked columns.
Enabled drilldowns for managers, products, sectors, and agents.

5. Automation & Refresh
Enabled scheduled data refresh using Power BI Gateway.
Deployed on Power BI Service for secure team-wide access.

## Tools & Stack
Power BI Desktop & Power BI Service – for modeling, visualizing, and publishing.
MySQL – backend data source.
ETL with Python & SQL – for data prep and cleansing.
Snowflake Schema – for optimized querying and report performance.
DAX – for dynamic calculations and custom metrics.

## Conclusion
This project helped Company modernize its data infrastructure, providing instant visibility into performance across accounts, products, sectors, and sales teams. The dashboards empower decision-makers with actionable insights that were previously buried in Excel files. By leveraging Power BI’s robust analytics features, the company can now make faster, more informed decisions and continue its path of global expansion with data as its backbone.

## 🙌 Acknowledgments  
Huge thanks to **Maven Analytics** for hosting such insightful challenges that push the boundaries of learning and creativity.  

## 🔗 Connect With Me  
Feel free to explore more of my projects and reach out:  
- [LinkedIn](https://www.linkedin.com/in/narendrasingh1402)
- [YouTube](https://www.youtube.com/@Analyst_Hive)  
- [Portfolio](https://narendra1402.github.io/)


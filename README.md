# EV Charging Intelligence & Revenue Optimization

An end-to-end data analytics project focused on understanding EV charging demand, revenue performance, station utilization, and expansion opportunities using Python, SQL, and Power BI.

## Project Overview

Electric vehicle charging networks need to understand when customers charge their vehicles, which stations perform well, how revenue varies over time, and where operational improvements may be needed.

This project analyzes a dataset containing **50,000+ EV charging sessions across 30 charging stations** to explore charging patterns, revenue trends, station performance, and expansion priorities.

The project follows a complete analytics workflow, from data preparation and exploratory analysis to SQL-based business analysis and interactive Power BI dashboards.

> **Note:** The dataset is used for portfolio analysis and should not be interpreted as verified operational data from a real EV charging network.

## Project Objectives

- Analyze charging session patterns and demand trends.
- Evaluate revenue performance across charging stations and time periods.
- Compare station utilization and operational efficiency.
- Identify high-performing and underperforming stations.
- Develop a priority-based framework for evaluating potential expansion opportunities.
- Present key performance indicators through interactive Power BI dashboards.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data processing and exploratory analysis |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical operations and analysis |
| Jupyter Notebook | Analysis workflow and documentation |
| SQL / PostgreSQL | Business queries and performance analysis |
| CTEs | Organizing multi-step SQL analysis |
| Window Functions | Ranking and comparing station performance |
| Power BI | Interactive dashboards and visual analytics |
| DAX | KPI calculations and analytical measures |
| Power Query | Data preparation and transformation |

## Project Workflow

1. **Data Preparation:** Reviewed the raw dataset and prepared the data for analysis.
2. **Data Cleaning:** Checked data quality, consistency, and key fields.
3. **Exploratory Data Analysis:** Used Python, Pandas, and NumPy to examine charging patterns and key variables.
4. **SQL Analysis:** Applied aggregations, CTEs, joins where required, and window functions to answer business questions.
5. **Data Modeling:** Prepared the analytical data for Power BI reporting.
6. **Dashboard Development:** Built five Power BI dashboard pages for different business perspectives.
7. **Business Interpretation:** Used KPIs and visual comparisons to highlight performance patterns and potential areas for improvement.

## Power BI Dashboard Suite

The project includes five dashboard pages designed to provide different views of EV charging performance.

### 1. Executive Overview

Provides a high-level summary of charging activity and overall performance using key metrics and trend visualizations.

![Executive Overview Dashboard](reports/dashboard_screenshots/01_executive_overview.png)

### 2. Revenue Performance

Examines revenue trends and compares revenue performance across stations and relevant time periods.

![Revenue Performance Dashboard](reports/dashboard_screenshots/02_station_performance.png)

### 3. Charging Demand Analysis

Explores charging session patterns across dates, months, and available time-based categories to understand demand variations.

![Charging Demand Dashboard](reports/dashboard_screenshots/03_demand_intelligence.png)

### 4. Station Utilization & Operational Efficiency

Compares station-level activity and utilization-related indicators to identify differences in operational performance.

![Station Utilization Dashboard](reports/dashboard_screenshots/04_revenue_intelligence.png)

### 5. Expansion & Priority Analysis

Uses station performance indicators and priority-based comparisons to support further evaluation of potential expansion opportunities.

![Expansion and Priority Dashboard](reports/dashboard_screenshots/05_expansion_strategy.png)

## Key Analytical Areas

- Total charging sessions and revenue analysis.
- Average charging duration and session-level comparisons.
- Revenue performance by station and time period.
- Charging demand trends and peak-period analysis.
- Station-level performance ranking using SQL window functions.
- Utilization and operational efficiency comparisons.
- Priority-based station evaluation for potential expansion.
- Interactive exploration using Power BI slicers and filters.

*The exact KPIs and findings depend on the available dataset fields and the measures implemented in the Power BI model.*

## Repository Structure

```text
EV-Charging-Intelligence-&-Revenue-Optimization/
│
├── data/
│   ├── ev_charging_sessions_raw.csv
│   ├── ev_charging_sessions_clean.csv
│   ├── ev_charging_sessions_engineered.csv
│   └── station_performance_metrics.csv
│
├── notebook/
│   └── 02_EDA.ipynb
│
├── powerbi/
│   └── EV_Charging_Intelligence_&_Revenue_Optimization.pbix
│
├── reports/
│   ├── dashboard_screenshots/
│   │   ├── 01-executive-overview.png
│   │   ├── 02_station_performance.png
│   │   ├── 03_demand_intelligence.png
│   │   ├── 04_revenue_intelligence.png
│   │   └── 05_expansion_strategy.png
│   │
│   ├── dashboard_report.pdf
│   └── REPORT.md
│
├── sql/
│   ├── 01_basic_analysis.sql
│   └── 02_advanced_analysis.sql
│
├── 01_Project_Setup.ipynb
└── README.md
```

## How to Explore the Project

### View the Power BI Dashboard

1. Open the `powerbi` folder.
2. Download `EV_Charging_Intelligence_Revenue_Analytics.pbix`.
3. Open the file using Microsoft Power BI Desktop.
4. Use the available slicers and filters to explore the dashboard pages.

### Explore the Python Analysis

1. Open the relevant `.ipynb` files in Jupyter Notebook.
2. Install the required Python libraries.
3. Update the dataset paths if necessary.
4. Run the notebook cells in order.

### Explore the SQL Queries

1. Open the `.sql` files in the `sql` folder.
2. Review the basic and advanced analytical queries.
3. Configure your database connection and table names to match your local setup before executing queries.

### Read the Dashboard Report

Open `reports/Dashboard_Report.pdf` for the dashboard report and `reports/REPORT.md` for the detailed written documentation.

## Skills Demonstrated

- Data cleaning and preparation
- Exploratory Data Analysis (EDA)
- SQL querying and analytical problem-solving
- Aggregations, CTEs, and window functions
- KPI development and DAX measures
- Power BI data modeling and visualization
- Business performance analysis
- Translating analytical results into business-oriented insights

## Future Improvements

- Integrate additional charging station and geographic data.
- Develop demand forecasting models using historical charging patterns.
- Add more detailed station-level profitability analysis where the required cost data is available.
- Evaluate expansion scenarios using additional location, demand, and infrastructure data.
- Automate data refresh and reporting workflows.

## Author

**Shagun Chauhan**

Aspiring Data Analyst | Python | SQL | Power BI | Excel


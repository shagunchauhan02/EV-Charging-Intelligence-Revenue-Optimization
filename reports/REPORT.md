# EV Charging Intelligence & Revenue Optimization
## Detailed Project Report

**Author:** Shagun Chauhan  
**Project Type:** End-to-End Data Analytics & Business Intelligence  
**Tools:** Python, Pandas, NumPy, SQL, PostgreSQL, Power BI, DAX

---

## 1. Executive Summary

EV Charging Intelligence & Revenue Optimization is an end-to-end data analytics project designed to explore charging activity, revenue performance, demand patterns, and operational efficiency across an electric vehicle charging network.

The project uses Python for data preparation and exploratory analysis, SQL for structured business analysis, and Power BI for interactive visualization and performance monitoring.

The solution includes five dashboards that provide complementary perspectives on executive performance, revenue, charging demand, station utilization, and station prioritization.

The primary objective is to transform charging session data into meaningful business intelligence that can support operational monitoring and data-informed planning.

## 2. Business Problem

As electric vehicle adoption grows, charging network operators need to understand charging behavior, station performance, revenue generation, and infrastructure utilization.

Analyzing raw session records alone does not provide an accessible view of overall business performance.

This project addresses the following business questions:

- How is charging activity distributed across stations?
- Which stations contribute most to recorded revenue?
- How does charging demand vary over time?
- What patterns can be identified in session duration?
- Which stations may require further operational investigation?
- How can performance indicators support infrastructure planning?

## 3. Project Objectives

- Prepare and validate charging session data.
- Perform exploratory data analysis using Python.
- Use SQL to investigate business questions and compare performance.
- Develop relevant KPIs and analytical measures.
- Build five interactive Power BI dashboards.
- Explore revenue and charging-demand patterns.
- Develop a structured approach to station prioritization.
- Communicate analytical results through business-focused visualizations.

## 4. Dataset Overview

The project uses a charging session dataset containing more than 50,000 sessions across 30 charging stations.

The dataset supports analysis of charging activity, station performance, time-based trends, duration, and revenue-related metrics.

The project includes raw, cleaned, and engineered data stages.

Data preparation and validation focus on:
- Reviewing column types and data consistency.
- Checking missing values and duplicate records.
- Preparing fields for analytical calculations.
- Validating revenue and duration calculations where applicable.
- Preparing structured data for SQL analysis and Power BI reporting.

*Note: The dataset is project data. Its origin and any simulated or generated fields should be described accurately if clarification is needed.*

## 5. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data preparation and exploratory analysis |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical operations |
| PostgreSQL / SQL | Business queries and analytical calculations |
| CTEs | Organizing complex queries into logical steps |
| Window Functions | Ranking and comparative analysis |
| Power BI | Interactive business intelligence dashboards |
| DAX | KPI measures and analytical calculations |
| Power Query | Data transformation |
| GitHub | Project documentation and version control |

## 6. Project Methodology

### 6.1 Data Preparation

The raw dataset was inspected and prepared for analysis using Python. The workflow focused on data types, data consistency, relevant fields, and validation checks.

### 6.2 Exploratory Data Analysis

Exploratory analysis was used to understand charging-session characteristics, station-level activity, revenue distribution, and time-based patterns.

### 6.3 Feature Engineering

An engineered dataset was prepared to support additional analytical dimensions and reporting requirements.

### 6.4 SQL Analysis

SQL was used to organize and investigate business data using filtering, conditional logic, aggregations, CTEs, window functions, and ranking techniques.

These methods support station comparisons and analysis across relevant time periods.

### 6.5 Power BI Reporting

The prepared dataset was used to build five dashboards. KPI cards, charts, slicers, and comparative views help users explore performance from different business perspectives.

### 6.6 Validation

Revenue and duration calculations were checked against relevant source fields where applicable. KPI definitions and validation logic should be interpreted alongside the actual implementation.

## 7. Power BI Dashboard Analysis

### Dashboard 1: Executive Overview

**Objective:** Provide a high-level view of charging network performance.

Analytical focus:
- Overall charging activity
- Revenue-related KPIs
- Session performance
- High-level business trends

**Business application:** Helps stakeholders review the overall state of the charging network.

### Dashboard 2: Revenue Performance

**Objective:** Explore revenue generation and differences in performance across stations and relevant business dimensions.

Analytical focus:
- Revenue distribution
- Station-level comparisons
- Revenue trends over time
- Relative contribution to overall revenue

**Business application:** Helps identify areas for deeper revenue-performance analysis.

### Dashboard 3: Charging Demand

**Objective:** Understand when charging activity occurs and how it changes over time.

Analytical focus:
- Time-based charging patterns
- Monthly and daily trends, where available
- Session distribution
- Potential peak and off-peak periods

**Business application:** Helps inform demand monitoring and operational planning.

### Dashboard 4: Station Utilization

**Objective:** Compare charging-station activity and investigate operational efficiency.

Analytical focus:
- Station-level utilization indicators
- Session duration
- Comparative charging activity
- Potential areas for operational investigation

**Business application:** Helps identify stations that may need further review.

*True capacity utilization requires suitable capacity and availability data. Session counts alone should not be treated as a complete utilization measure.*

### Dashboard 5: Expansion & Priority Analysis

**Objective:** Structure station comparisons to support operational prioritization and potential expansion assessment.

Analytical focus:
- Station performance indicators
- Revenue and demand patterns
- Utilization-related indicators
- Priority criteria defined in the analytical model

**Business application:** Helps shortlist stations for further evaluation. Expansion decisions require additional financial, geographic, grid-capacity, and market-demand information.

## 8. Key Performance Indicators

The project focuses on business metrics such as:

| KPI | Definition / Purpose |
|---|---|
| Total Revenue | Sum of recorded session revenue |
| Total Charging Sessions | Count of charging sessions |
| Average Revenue per Session | Total revenue divided by the number of eligible sessions |
| Average Charging Duration | Average duration across valid sessions |
| Station Utilization | Utilization based on the available capacity and time definitions |
| Station Priority Count | Number of stations meeting the defined priority criteria |

The final KPI definitions should match the DAX measures and business rules implemented in the Power BI model.

## 9. Business Value

The analytical solution demonstrates how charging-session data can be used to:

- Monitor business performance.
- Compare station-level revenue and charging activity.
- Investigate time-based demand patterns.
- Evaluate station performance using consistent indicators.
- Identify potential operational improvement opportunities.
- Support evidence-based discussions about network planning.

The project provides analytical support rather than a definitive financial or infrastructure investment recommendation.

## 10. Limitations

- Findings depend on the completeness and quality of the available dataset.
- Historical patterns do not necessarily predict future charging demand.
- Revenue does not automatically represent profit.
- Utilization analysis depends on the availability and definition of charging capacity.
- Expansion assessment requires additional cost, location, grid, and competitor data.
- Any generated or simulated data should not be interpreted as verified real-world operating results.

## 11. Future Enhancements

Potential improvements include:

- Charging-demand forecasting.
- Geographic coverage and location analysis.
- Electricity cost and profitability analysis.
- Automated data refresh and reporting.
- Predictive maintenance indicators.
- A documented station-expansion scoring model.
- Integration with live charging infrastructure data.

## 12. Conclusion

EV Charging Intelligence & Revenue Optimization demonstrates an end-to-end analytics workflow combining data preparation, exploratory analysis, SQL querying, KPI development, and interactive business intelligence reporting.

The project illustrates how technical analytics skills can be applied to an operational business problem and translated into a structured reporting solution.

**Core Skills:** Python, SQL, PostgreSQL, Data Cleaning, EDA, Feature Engineering, CTEs, Window Functions, Power BI, DAX, Data Modeling, Data Visualization, and Business Intelligence.

---

**Author:** Shagun Chauhan  
**Project:** EV Charging Intelligence & Revenue Optimization

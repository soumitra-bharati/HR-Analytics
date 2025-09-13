# HR-Analytics
# Overview
This repository contains an interactive HR Metrics Dashboard built using Power BI, designed to visualize key workforce metrics such as employee turnover rates, recruitment efficiency proxies (e.g., median years at company), and diversity statistics. The project sources data from the public IBM HR Analytics Employee Attrition dataset on Kaggle, performs data cleaning and analysis, and incorporates dynamic filters for leadership-level reporting.
The dashboard analyzes a sample workforce of 1,470 employees, revealing insights like a 16.12% attrition rate, moderate job satisfaction (avg. 2.8-3.0 on a 4-point scale), and diversity trends (e.g., STEM-dominant attrition). It supports strategic decision-making by highlighting patterns in attrition by demographics, tenure, roles, and departments (Human Resources, Research & Development, Sales). An accompanying report (included as HR Analytics Dashboard Report.pdf) provides detailed analysis, benchmarks, and actionable recommendations to reduce turnover below 10%, improve satisfaction, and enhance diversity.
This project demonstrates proficiency in data visualization, HR analytics, and KPI tracking, aligning with roles focused on creating dashboards for organizational insights.

# Features

- Interactive Visualizations: Cards, charts (bar, pie, line), and tables for metrics like total employees (1,470), attrition (237), average age (37), median salary ($5,000), and median tenure (5 years).
- Attrition Breakdowns: By gender (males: 150/63.3%), age group (30-50: 123), education field (Life Sciences: 37.55%), tenure (peaks at year 1: 60), and job roles (Lab Technician: 62 highest).
- Diversity Insights: Gender splits, age distributions, and education field dominance, supporting inclusive reporting.
- Job Satisfaction Analysis: Role-based ratings (e.g., Managers avg. ~2.7), with department rankings (R&D ~3.2 highest, Sales ~2.2 lowest).
- Filters and Drill-Downs: Department slicers for targeted views; benchmarks against 2025 U.S. averages (e.g., 13.0% national separation rate).
- Actionable Recommendations: Strategies for reducing attrition (e.g., enhanced onboarding), improving satisfaction (e.g., transparent feedback), and boosting diversity (e.g., inclusive recruitment).

# Technologies Used

- Power BI: For dashboard development, DAX measures, and visualizations.
- Data Sources: Kaggle's IBM HR Analytics dataset (CSV/Excel format).
- Data Processing: Excel or SQL for cleaning; Power Query for transformations.
- Analysis Tools: DAX for metrics like attrition rate = (Attritions / Total Employees) * 100.

# Usage

- Explore the Dashboard: Open in Power BI, apply filters (e.g., by department), and interact with visuals for real-time insights.
- View the Report: Open HR Analytics Dashboard Report.pdf for in-depth analysis and recommendations.
- Customize: Edit DAX measures or add columns (e.g., for true time-to-hire if extending the dataset).

- Example Insights:
  High attrition in R&D/Sales suggests targeted retention bonuses.
  STEM attrition dominance indicates diversification needs.

# Data Source and Limitations

- Dataset: Simulated employee records from Kaggle (1,470 rows, columns like Age, Attrition, Department, JobRole, JobSatisfaction).
- Proxies Used: Median years at company as recruitment efficiency stand-in (due to lack of direct time-to-hire data).
- Benchmarks: Compared to 2025 U.S. averages (e.g., 22% overall turnover, 13.0% separation rate for tech/R&D).
- Privacy Note: Anonymized data; no real employee info used.

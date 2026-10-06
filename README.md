# Electricity Consumption Analysis & Power Demand Dashboard

## Project Overview
This project analyzes hourly electricity consumption to identify usage trends,
peak-demand periods, daily/monthly patterns, and unusual observations.

**Data note:** The included dataset is synthetic/simulated data created for portfolio learning.
It should not be presented as utility-company or real-world measured data.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Power BI

## Workflow
1. Load raw electricity data.
2. Check missing values and duplicates.
3. Convert date/time fields and create time-based features.
4. Analyze hourly, daily, monthly, and weekday consumption.
5. Classify peak observations using the 90th percentile.
6. Export a cleaned CSV.
7. Import the cleaned CSV into Power BI and build an interactive dashboard.

## Key Analysis
- Total electricity consumption
- Average hourly consumption
- Peak and minimum demand
- Hourly demand profile
- Daily consumption trend
- Monthly consumption
- Day-of-week patterns
- Peak vs normal observations

## Power BI Dashboard
Recommended visuals:
- Total Consumption KPI
- Average Consumption KPI
- Peak Demand KPI
- Minimum Demand KPI
- Daily Consumption line chart
- Monthly Consumption column chart
- Hourly Consumption line chart
- Day-of-Week bar chart
- Peak vs Normal chart
- Date/Month/Hour/Peak slicers

## Resume Project Description
- Analyzed hourly electricity consumption data using Python, Pandas, and NumPy to identify usage trends and peak-demand periods.
- Cleaned and transformed time-series data, including duplicate removal, missing-value handling, datetime conversion, and feature creation.
- Built Matplotlib visualizations and prepared a Power BI-ready dataset for an interactive consumption and demand dashboard.

## Repository Structure
- `data/raw/` - raw synthetic dataset with intentional data-quality issues
- `data/cleaned/` - cleaned dataset for analysis and Power BI
- `notebooks/` - analysis notebook
- `visualizations/` - exported Matplotlib charts
- `powerbi/` - place the `.pbix` dashboard here

# Term Deposit Conversion Analysis

Power BI & statistical analysis of a bank's term deposit marketing campaign (UCI Bank Marketing dataset, public).

## Overview
Analysis of a Portuguese bank's telemarketing campaign data (45,000+ records) to identify the demographic and behavioral drivers of term-deposit conversion, with an interactive Power BI dashboard and a written analytical report.

## Tools
- Power BI (cards, slicers, bar/donut/line/column/pie charts)
- DAX
- Statistical analysis

## Key Additions
- Identified and corrected a measurement error in the dashboard where conversion was charted as a raw count instead of a rate, which had been visually overstating the management segment's performance. The corrected metric showed students and retirees convert at more than double the rate of management.
- Added a new "Call & Contact Insights" page quantifying call duration and prior-contact effects: customers previously contacted convert at 23% versus 9% for first-time contacts.
- Rewrote the analytical report's findings and recommendations using figures computed directly from the raw data (e.g., conversion rate by job, education, and campaign month).

## Files
- `Banking data.csv` — source dataset
- `Banking Dataset - Marketing Targets.pbix` — Power BI report
- `Banking_Report_file (1).docx` — written analytical report

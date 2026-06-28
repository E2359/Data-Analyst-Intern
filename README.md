# Data Analyst Intern Report

## Project Overview

This project is a restaurant business analysis for **Chicken GoGo**, completed in the style of a **Data Analyst Intern** project. The goal is to use real business files such as sales records, payroll data, employee schedules, time clock records, menu prices, and supplier price lists to understand restaurant performance and provide practical recommendations.

The final deliverable is an HTML report called:

`Data_Analyst_Intern_Report.html`

The report is designed to be opened directly in a browser and shared with managers, restaurant owners, or included as a portfolio project.

## Business Questions

This analysis focuses on several restaurant operation questions:

1. How much revenue did the restaurant generate during the sales period?
2. Which days had stronger or weaker sales performance?
3. How much of the sales came from card payments, cash payments, and tips?
4. Are labor hours and payroll reasonable compared with sales activity?
5. Are employees scheduled properly based on business needs?
6. Are there possible payroll, schedule, or time clock issues that should be reviewed?
7. Which suppliers may offer lower listed prices for certain products?
8. What actions can the business take to improve operations and cost control?

## Files Included

| File | Description |
|---|---|
| `Data_Analyst_Intern_Report.html` | Final professional HTML report with KPIs, charts, tables, findings, and recommendations. |
| `ChickenGoGo_Data_Analyst_Intern_Restaurant_Analysis.ipynb` | Jupyter Notebook version of the full analysis. |
| `chickengogo_converted/` | Folder containing converted `.xlsx` files from Apple Numbers files. |
| `cleaned_data/` | Cleaned CSV files created during the analysis process. |
| `charts/` | Saved chart images used in the report and notebook. |
| `README.md` | Project explanation and documentation. |

## Data Sources

The project uses restaurant operation files, including:

- Daily sales/accounting records
- Payroll records
- Employee schedule files
- Employee clock-in/clock-out records
- Menu price list
- Ingredient/material purchasing list
- Supplier price comparison file
- Startup or front-of-house cost records

Some original files were in Apple Numbers format (`.numbers`). These were converted into Excel format (`.xlsx`) so they could be loaded and analyzed in Python.

## Tools Used

- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- openpyxl
- HTML/CSS for report formatting

## Analysis Performed

The analysis includes:

### 1. Data Cleaning

- Loaded Excel and converted Numbers files
- Standardized column names
- Removed empty rows and unnecessary formatting rows
- Converted date, time, sales, tip, payroll, and cost fields into usable formats
- Checked missing values and unusual records

### 2. Sales Analysis

- Calculated total sales
- Compared daily sales trends
- Reviewed card sales, cash sales, and tip amounts
- Created sales trend charts and payment method summaries

### 3. Labor and Payroll Analysis

- Reviewed employee payroll data
- Compared scheduled labor with time clock records
- Estimated total labor hours
- Calculated labor-related KPIs, including sales per labor hour when possible
- Flagged possible payroll or clock-in records that may need manager review

### 4. Schedule Coverage Analysis

- Reviewed employee schedules by day and role
- Checked front desk and kitchen coverage
- Identified possible gaps in staffing coverage
- Compared staffing needs with business operation times

### 5. Menu and Supplier Analysis

- Reviewed menu pricing
- Compared supplier price records
- Identified items where one supplier may have a lower listed price
- Suggested ways to improve purchasing and inventory decisions

### 6. Business Recommendations

The report provides manager-ready recommendations in areas such as:

- Sales tracking
- Labor scheduling
- Payroll review
- Inventory purchasing
- Supplier comparison
- Data collection improvements

## Key Skills Demonstrated

This project demonstrates practical data analyst intern skills, including:

- Data cleaning and preparation
- Spreadsheet conversion and organization
- Exploratory data analysis
- KPI development
- Business reporting
- Data visualization
- Operational analysis
- Restaurant labor and sales analysis
- Translating raw business files into actionable recommendations

## How to View the Report

Open the file below in any browser:

`Data_Analyst_Intern_Report.html`

For the full technical workflow, open:

`ChickenGoGo_Data_Analyst_Intern_Restaurant_Analysis.ipynb`

## Limitations

This analysis is based on the files provided. Some business questions would be stronger with more complete data, such as:

- Item-level sales by menu product
- Hourly sales by time of day
- Exact ingredient usage per menu item
- Waste records
- Customer counts
- Delivery platform reports
- Longer sales history across multiple months

Because of these limitations, some conclusions should be treated as operational signals instead of final business decisions.

## Next Steps

Recommended next steps for the restaurant:

1. Track item-level sales every day.
2. Record hourly sales to improve staffing decisions.
3. Keep a consistent inventory log.
4. Compare supplier prices monthly.
5. Track waste and ingredient usage.
6. Build a weekly dashboard for sales, labor, and inventory.

## Project Summary

This project shows how a data analyst intern can support a restaurant by turning messy business spreadsheets into a clean, organized, and professional report. The analysis helps the business better understand sales performance, labor efficiency, schedule coverage, purchasing decisions, and areas for operational improvement.

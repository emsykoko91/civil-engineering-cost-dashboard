# Commercial Cost Control Dashboard

> An interactive Excel cost-control and executive reporting solution for a simulated civil engineering project portfolio.

![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Commercial%20Dashboard-217346?logo=microsoftexcel&logoColor=white)
![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Cost%20Analysis%20%7C%20Reporting%20%7C%20Dashboard-blue)

## Dashboard Preview

![Commercial Cost Control Dashboard](screenshots/dashboard.png)

## Project Overview

This project demonstrates the design and development of an interactive commercial cost-reporting solution in Microsoft Excel.

The project was created to simulate the responsibilities of a Cost and Data Analyst working within a civil engineering business. It provides management with a consolidated view of project budgets, actual expenditure, cost categories, supplier spend and overall project health.

The workbook follows a structured reporting architecture that separates:

- source and reference data;
- calculation and reconciliation logic;
- analytical reporting;
- executive dashboard presentation.

## Business Challenge

Commercial and project managers need reliable financial information to answer questions such as:

- Are projects operating within their approved budgets?
- How much of the portfolio budget has been used?
- Which projects have incurred the highest costs?
- Which cost categories are driving expenditure?
- Which suppliers account for the greatest spend?
- Which projects require management attention?

Without a structured reporting solution, answering these questions can require repeated manual analysis across several spreadsheets.

## Solution

I developed a single Excel workbook containing linked master-data, transaction, calculation and reporting sheets.

The solution includes:

- relational workbook design;
- project and client master tables;
- cost-category reference data;
- project budget allocation;
- transaction-level actual-cost data;
- budget and actual-cost reconciliation;
- category-level variance analysis;
- supplier and expenditure analysis;
- interactive Pivot Tables and Pivot Charts;
- KPI cards and slicers;
- a management-focused commercial dashboard.

## Key Achievements

- Built a structured Excel reporting model from the ground up.
- Used lookup tables to reduce duplicated information and improve data integrity.
- Automated project and category retrieval using `XLOOKUP`.
- Aggregated expenditure using single- and multi-condition `SUMIFS`.
- Reconciled project budgets against actual expenditure.
- Analysed costs by project, category, month and supplier.
- Created an interactive dashboard for executive reporting.
- Converted detailed financial analysis into concise commercial insights.

## Dashboard Features

The executive dashboard provides:

- Total Contract Value
- Total Cost Budget
- Actual Spend
- Remaining Budget
- Planned Margin
- Active Projects
- Monthly Spend Trend
- Budget versus Actual Spend
- Cost Category Analysis
- Top Supplier Analysis
- Project Health Monitoring
- Commercial Insights
- Interactive Project and Cost Category filters

## Workbook Structure

```text
Civil Engineering Cost Control.xlsx

├── Projects
├── Clients
├── Cost Categories
├── Budget
├── Actual Costs
├── Cost Reconciliation
├── Variance Analysis
├── Dashboard_Data
├── Pivot Analysis
└── Dashboard
```

## Reporting Architecture

```text
Master and Transaction Data
            ↓
Calculation and Reconciliation Layer
            ↓
Pivot Analysis and Reporting Layer
            ↓
Executive Commercial Dashboard
```

## Excel Skills Demonstrated

### Data modelling

- Excel Tables
- Structured references
- Primary and lookup keys
- Master data versus transaction data
- Relational workbook design
- Data validation

### Formulas

- `XLOOKUP`
- `SUMIFS`
- `IF`
- `IFERROR`
- `EOMONTH`
- Percentage and variance calculations

### Analysis

- Budget allocation
- Cost reconciliation
- Variance analysis
- Budget utilisation
- Monthly expenditure analysis
- Supplier concentration analysis
- Cost-category analysis

### Reporting and visualisation

- Pivot Tables
- Pivot Charts
- Slicers
- KPI cards
- Conditional formatting
- Executive dashboard design
- Commercial commentary

## Key Business Insights

The analysis of the simulated portfolio identified that:

- Materials represented approximately **40.5%** of recorded expenditure and were the largest cost category.
- BuildForce Labour was the highest-spend supplier at approximately **£283,000**.
- Total actual expenditure was approximately **£3.04 million**.
- Portfolio budget utilisation was approximately **14.9%**.
- All projects remained within their approved cost budgets during the reporting period.
- Bridge Alpha had the highest project-level expenditure, reflecting its size and earlier delivery activity.

## Repository Structure

```text
civil-engineering-cost-dashboard/
│
├── README.md
│
├── workbook/
│   └── Civil Engineering Cost Control.xlsx
│
├── screenshots/
│   └── dashboard.png
│
├── documentation/
│   └── Project Documentation.pdf
│
└── presentation/
    └── Executive Presentation.pptx
```

The documentation and presentation folders will be added as the portfolio pack is completed.

## Tools Used

- Microsoft Excel
- Excel Tables and structured references
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional formatting
- GitHub for project documentation and version control

## What I Learned

This project strengthened my ability to:

- structure an Excel workbook as a scalable reporting model;
- select formulas based on business requirements;
- reconcile budget and actual financial information;
- identify important project cost drivers;
- design reports for management rather than only for analysts;
- translate detailed analysis into clear commercial insights;
- separate raw data, calculation and presentation layers.

## Future Enhancements

Potential future improvements include:

- Power Query automation for monthly data imports;
- data-quality and exception-reporting controls;
- cash-flow monitoring;
- cost forecasting and estimate-at-completion analysis;
- automated commercial commentary;
- Power BI implementation;
- dynamic project-risk indicators.

## Disclaimer

This project uses entirely simulated data and was created for learning and portfolio purposes. It does not contain confidential company or client information.

## Author

**Adanu Emmanuel Okoko**

Data Analyst | Business Intelligence | Commercial Reporting


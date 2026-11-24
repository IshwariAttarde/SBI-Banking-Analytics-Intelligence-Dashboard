# SBI Banking Analytics & Intelligence Dashboard

An end-to-end **Banking & Financial Services (BFSI) business intelligence project** built with Microsoft Power BI, DAX, Power Query, and Microsoft Excel. The solution brings six analytical views together to explore financial performance, customer behaviour, lending risk, branch operations, transaction activity, and customer retention.

> **Project context:** This is an independent, SBI-inspired portfolio project. The included workbook is a **synthetic banking dataset** created for analytics and demonstration purposes; it is not official State Bank of India data and this project is not affiliated with or commissioned by SBI.

## Live Power BI Dashboard

[**Open the interactive dashboard**](https://app.powerbi.com/view?r=eyJrIjoiMzFlOTk4MTgtNzQ1Yy00ZDZhLTg1YzUtY2U2MjZhOTFiNDZkIiwidCI6ImM5YzUwODQ4LWIwM2EtNGJlNC1iNjU1LTZlZGQ3ZmI4MWM1YSJ9)

## Dashboard Modules

### 1. Executive Banking Dashboard
- Tracks revenue, customer base, advances, deposits, gross NPA, net profit, ROA, and ROE.
- Reviews monthly financial trends and business mix.
- Compares state performance and leading banking products.
- Surfaces high-level performance indicators for management review.

![Executive Banking Dashboard](assets/screenshots/01-executive-banking-dashboard.png)

### 2. Customer 360° Analytics
- Explores customer demographics by age, gender, location, income, and occupation.
- Segments customers into Mass, Affluent, High Value, NRI, and Other groups.
- Analyses product holdings, average balance, customer lifetime value, and customer journey.
- Provides an individual customer view for relationship analysis.

![Customer 360 Analytics](assets/screenshots/02-customer-360-analytics.png)

### 3. Loan & Credit Risk Analytics
- Reviews loan portfolio composition across retail, corporate, MSME, agriculture, and other segments.
- Monitors gross NPA, net NPA, and portfolio trends.
- Analyses Probability of Default (PD), Exposure at Default (EAD), and Loss Given Default (LGD).
- Examines borrower exposure, sector risk, and provision coverage.

![Loan and Credit Risk](assets/screenshots/03-loan-and-credit-risk.png)

### 4. Branch & Regional Performance
- Compares branch distribution and performance across states and regions.
- Tracks deposits, advances, CASA ratio, profitability, and growth.
- Identifies leading branches and state-level performance patterns.
- Reviews branch network expansion and branch-type contribution.

![Branch and Regional Performance](assets/screenshots/04-branch-and-regional-performance.png)

### 5. Transaction Analytics
- Tracks transaction volume, transaction value, and average transaction value.
- Compares digital and branch-based channels, including UPI, mobile banking, internet banking, and ATM.
- Analyses transaction categories, merchant activity, and customer segments.
- Uses trend analysis, heatmaps, treemaps, and transaction-flow visualisation.

![Transaction Analytics](assets/screenshots/05-transaction-analytics.png)

### 6. Customer Churn & Retention
- Monitors total, churned, and retained customers alongside churn and retention rates.
- Compares churn across customer segments and products.
- Uses cohort analysis to examine retention over time.
- Reviews churn drivers and retention campaign performance.

![Customer Churn and Retention](assets/screenshots/06-customer-churn-and-retention.png)

## Tools & Technologies

- **Microsoft Power BI** — report development, interactive visuals, and data modelling
- **DAX** — calculated measures, KPI logic, and analytical calculations
- **Power Query** — data cleaning and transformation
- **Microsoft Excel** — source workbook and structured analytical tables

## Dataset

The Excel workbook is available at:

`data/SBI_PowerBI_Synthetic_Banking_Dataset_2023_2025_Updated_AcquisitionDates.xlsx`

It contains dimension, fact, bridge, reference, and measure-definition sheets, including:

- Dimensions: `DimDate`, `DimBranch`, `DimProduct`, `DimCustomer`
- Facts: `FactAccount`, `FactLoan`, `FactTransaction`, `FactBankMonthly`, `FactBranchMonthly`, `FactCustomerMonthly`
- Supporting tables: `FactCohortRetention`, `FactChurnReason`, `FactTargets`, `FactBusinessMix`, `BridgeCustomerProduct`
- Documentation: `DataDictionary`, `PowerBI_Relationships`, `PowerBI_Measures`

The workbook name indicates a 2023–2025 synthetic dataset. The published report currently displays a Jan 2023–Dec 2023 reporting selection in the supplied screenshots. Use the report's date slicer to explore the available period.

## Repository Structure

```text
SBI-Banking-Analytics-Intelligence-Dashboard/
├── README.md
├── .gitignore
├── data/
│   └── SBI_PowerBI_Synthetic_Banking_Dataset_2023_2025_Updated_AcquisitionDates.xlsx
└── assets/
    └── screenshots/
        ├── 01-executive-banking-dashboard.png
        ├── 02-customer-360-analytics.png
        ├── 03-loan-and-credit-risk.png
        ├── 04-branch-and-regional-performance.png
        ├── 05-transaction-analytics.png
        └── 06-customer-churn-and-retention.png
```

## How to Explore

1. Open the [live Power BI report](https://app.powerbi.com/view?r=eyJrIjoiMzFlOTk4MTgtNzQ1Yy00ZDZhLTg1YzUtY2U2MjZhOTFiNDZkIiwidCI6ImM5YzUwODQ4LWIwM2EtNGJlNC1iNjU1LTZlZGQ3ZmI4MWM1YSJ9).
2. Use the available date and category slicers to interact with the report.
3. Navigate through the six dashboard modules.
4. Download the Excel workbook from `data/` to inspect the source tables and supporting documentation.

## Key Analytical Areas

| Area | Example metrics and analysis |
|---|---|
| Financial performance | Revenue, deposits, advances, net profit, ROA, ROE |
| Asset quality and credit risk | Gross NPA, net NPA, PD, EAD, LGD, provisions |
| Customer intelligence | Segments, demographics, product holdings, CLV |
| Branch operations | Branches, regional deposits, advances, CASA, profitability |
| Transaction behaviour | Volume, value, channel mix, category, time patterns |
| Customer retention | Churn rate, retained customers, cohort retention, churn drivers |

## Notes

- The dataset is synthetic and intended for learning, demonstration, and portfolio presentation.
- Dashboard metrics and visuals should be interpreted as outputs from this sample analytical model, not as verified SBI business disclosures.
- The repository contains the Excel source workbook and dashboard screenshots. The Power BI `.pbix` file is not included in this package.

## Author

**Ishwari Attarde**  
Data Analyst | Power BI | SQL | Excel | Python


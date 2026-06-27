# Tapestry Inc. – Discounted Cash Flow (DCF) Valuation

> A comprehensive financial valuation project integrating **Excel**, **Python**, and **Tableau** to estimate the intrinsic value of Tapestry Inc. (NYSE: TPR) using a Discounted Cash Flow (DCF) model.

---

## Project Overview

This project performs an end-to-end valuation of **Tapestry Inc.**, the parent company of Coach, Kate Spade, and Stuart Weitzman.

The objective was to:

- Analyze historical financial performance (FY2021–FY2025)
- Forecast operating performance (FY2026E–FY2030E)
- Estimate Enterprise and Equity Value using the DCF methodology
- Calculate intrinsic value per share
- Build an interactive Tableau dashboard to visualize historical trends and financial forecasts

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Financial Modeling & DCF |
| Python | Financial Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Calculations |
| Matplotlib | Data Visualization |
| Tableau | Interactive Dashboard |

---

##Repository Structure

```text
tapestry-dcf-valuation/
│
├── README.md
│
├── data/
│   ├── tableau_dataset.csv
│   └── raw_financials.xlsx
│
├── excel/
│   └── DCF_TPR.xlsx
│
├── python/
│   ├── Tapestry_DCF_Analysis.ipynb
│   └── requirements.txt
│
├── tableau/
│   ├── Tapestry_Dashboard.twbx
│   └── dashboard.png
│
├── images/
│   ├── dashboard.png
│   ├── revenue_trend.png
│   ├── profitability.png
│   └── fcff_trend.png
│
└── LICENSE
```

---

## Valuation Summary

| Metric | Value |
|---------|-------:|
| Revenue CAGR | **4.65%** |
| Terminal Growth Rate | **2.50%** |
| WACC | **11.6%** |
| Enterprise Value | **$12.54 Billion** |
| Net Debt | **$1.29 Billion** |
| Equity Value | **$11.24 Billion** |
| Intrinsic Value per Share | **$50.54** |

---

## Dashboard Preview

> Replace the image below with your exported Tableau dashboard.

```markdown
![Dashboard](images/dashboard.png)
```

---

## Key Visualizations

- Revenue Trend (Historical vs Forecast)
- Profitability Margin Analysis
- Free Cash Flow to Firm (FCFF) Trend
- Executive Dashboard (Tableau)

---

## Methodology

### 1. Historical Financial Analysis

Historical financial statements (FY2021–FY2025) were analyzed to identify key trends in:

- Revenue
- Gross Profit
- EBIT
- NOPAT
- Capital Expenditure
- Working Capital
- Free Cash Flow

---

### 2. Financial Forecasting

Financial statements were projected for FY2026E–FY2030E using assumptions for:

- Revenue Growth
- Gross Margin
- EBIT Margin
- Tax Rate
- Capital Expenditure
- Working Capital
- Depreciation & Amortization

---

### 3. Discounted Cash Flow (DCF)

The valuation follows the standard FCFF methodology:

```text
Enterprise Value =
PV of Forecast FCFF
+
PV of Terminal Value
```

Where:

- Terminal Growth Rate = 2.5%
- WACC = 11.6%

---

### 4. Equity Valuation

```text
Equity Value = Enterprise Value − Net Debt
```

```text
Intrinsic Value per Share =
Equity Value ÷ Shares Outstanding
```

---

## Python Analysis

Python was used to:

- Import financial data from Excel
- Calculate financial KPIs
- Generate trend visualizations
- Export a Tableau-ready dataset

Libraries used:

```python
pandas
numpy
matplotlib
openpyxl
```

---

## Tableau Dashboard

The dashboard provides an executive summary of the valuation through:

- Revenue Trend
- Profitability Margins
- FCFF Trend
- Historical vs Forecast Comparison

---

## Key Skills Demonstrated

- Financial Statement Analysis
- Discounted Cash Flow (DCF) Valuation
- Financial Forecasting
- WACC Calculation
- Enterprise & Equity Valuation
- Python for Financial Analytics
- Data Visualization
- Tableau Dashboard Development
- Business Storytelling

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

- Building an integrated financial model
- Forecasting operating performance
- Applying corporate finance concepts to real-world valuation
- Automating financial analysis using Python
- Communicating insights through interactive dashboards

---

# Excel MIS Sales Performance Dashboard

An interactive Excel-based MIS dashboard built to analyse sales performance, monitor KPIs, evaluate regional and salesperson performance, and support business decision-making.

## Project Overview

This project simulates a real-world sales reporting scenario in which management needs a consolidated view of sales performance across regions, salespeople, products and order statuses.

The objective was to transform raw sales data into a structured, interactive reporting dashboard using Microsoft Excel.

## Business Objectives

- Monitor total completed sales and order volumes.
- Calculate Average Order Value (AOV).
- Identify top-performing salespeople.
- Compare sales performance across regions.
- Analyse monthly sales trends.
- Monitor completed, pending and cancelled orders.
- Identify and address data-quality issues.

## Tools and Techniques

- Microsoft Excel
- Advanced Excel formulas: IF, IFERROR, SUMIFS, COUNTIF, AVERAGEIF
- Lookup functions: VLOOKUP, XLOOKUP, INDEX + MATCH
- Data cleaning: TRIM, PROPER
- Excel Tables and structured references
- PivotTables and PivotCharts
- Interactive slicers
- KPI reporting and dashboard design

## Dashboard Preview

![Excel MIS Sales Dashboard](dashboard-preview.png)

## Key Dashboard Metrics

| KPI | Result |
|---|---:|
| Total Completed Sales | ₹25,49,600 |
| Completed Orders | 36 |
| Average Order Value | ₹70,822.22 |
| Top Salesperson | Asha |
| Top Salesperson Sales | ₹7,87,350 |

## Dashboard Features

1. KPI cards for key sales metrics.
2. Monthly sales trend analysis.
3. Regional sales comparison.
4. Salesperson performance ranking.
5. Order status distribution.
6. Region and salesperson slicers for interactive filtering.

## Data Quality and Validation

The dataset included intentional data-quality issues, such as:

- Missing salesperson information.
- Missing order dates.
- Inconsistent text formatting and extra spaces.
- Negative unit quantities.
- Invalid discount percentages.
- Product and category mismatches.

Cleaning and validation techniques were applied while preserving the original raw data.

## Reporting Assumptions

- Sales performance KPIs use completed orders only.
- Pending and cancelled orders are excluded from completed sales.
- Transactions with missing dates remain included in total completed sales but are excluded from monthly trend analysis.
- Missing salesperson attribution is reported as Unassigned.

## Files Included

- `Excel_MIS_Sales_Dashboard_Portfolio.xlsx` — Interactive Excel dashboard and supporting worksheets.
- `dashboard-preview.png` — Dashboard screenshot.

## Key Learnings

This project provided practical experience in transforming raw business data into management-ready reports, validating data quality, building interactive dashboards and communicating business performance through KPIs and visualisations.

---

**Project Type:** Sales MIS Reporting & Dashboard Development  
**Tool:** Microsoft Excel  
**Status:** Completed

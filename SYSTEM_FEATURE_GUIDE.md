# Tableau Stimulator — Detailed System Feature Guide

## 👤 Creator / Owner Details Embedded in the Platform

**Adewale Samson Adeagbo** is embedded across the application interface and documentation as the creator and owner of Tableau Stimulator.

| Item | Details |
|---|---|
| Name | Adewale Samson Adeagbo |
| Location | Lagos, Nigeria |
| Identity | Data Scientist · STEM Educator · EdTech Builder · AI-Augmented Solutions Developer |
| Experience | 15+ years teaching Nursery, Primary and Secondary learners across Mathematics, Further Mathematics, Physics, Chemistry and Computer Science |
| Education | B.Sc.(Ed) Computer Science Education, Lagos State University, 2023 |
| Brand | Founder / Visioner of HMG Concepts — HMG Academy, HMG Technologies and HMG Media |
| Portfolio | https://cssadewale.pages.dev |
| HMG Concepts | https://hmgconcepts.pages.dev |
| GitHub | https://github.com/cssadewale |
| LinkedIn | https://linkedin.com/in/adewalesamsonadeagbo |
| YouTube | https://youtube.com/@hmgconcepts |
| WhatsApp | +234 810 086 6322 |
| Email | hmgconcepts@gmail.com · hismarvellousgrace@gmail.com |

Inside the app, users can click **“by Adewale Samson Adeagbo”** in the topbar to open the full About modal.


This guide explains the enhanced Tableau-style analytics system. It preserves all existing features and adds new free, browser-only capabilities. No paid service, backend, database, or AI API is required.

## 1. Tableau-Style Workspace

- **Worksheet:** Main analysis canvas. Drag fields to COLS and ROWS, select chart type, aggregation, sorting, labels, trend, forecast and filters.
- **Shelves:** COLS controls the X/category axis; ROWS controls numeric measures. Multiple ROWS create multi-series charts.
- **Marks:** Color By, Size By and Label behave like mark encodings. They change how data points are drawn without changing the raw dataset.
- **Workbook Sheets:** Add unlimited sheets. Each sheet keeps independent shelves, filters, chart type, title, annotations and reference lines.

## 2. Charting and Visual Analytics

Supported visuals include Bar, Horizontal Bar, Stacked Bar, Line, Area, Stacked Area, Scatter, Pie, Donut, Radar, Heatmap, Box Plot, Waterfall, Funnel and Gauge.

### New v8 chart improvements

- **Waterfall:** Shows positive and negative changes as a bridge to a final value.
- **Funnel:** Shows stage-by-stage conversion or drop-off.
- **Gauge:** Shows one KPI against an automatic numeric range.
- **Forecast (🔮):** Adds a five-step linear forecast calculated locally from the current aggregated series.
- **Moving Average (Ⓜ MA):** Adds a 3-point rolling average to smooth noisy trends.

## 3. Show Me / Template Picker

The 📋 button provides a Tableau-style chart recommendation workflow. Pick a goal such as Sales Ranking, Trend Over Time, Part of Whole, Funnel, Waterfall, KPI Gauge or Correlation. The system sets chart type, aggregation and sort defaults. You then place fields on shelves.

## 4. Calculated Fields

Use the top formula bar or ƒ modal. Field names are referenced in square brackets:

```text
[Revenue] - [Cost]
[Sales] / [Target] * 100
[Units] * [Price]
```

Calculated fields appear in the Data Pane and can be used like normal fields.

## 5. Filters, Top N, Reference and Goal Lines

- **Field filters:** Drag a field to Filters. Numeric fields become range filters; text fields become checkbox filters.
- **Top N:** Show only top or bottom N aggregated categories.
- **Reference lines:** Add fixed values or automatic mean/median/min/max lines.
- **Goal line:** Add a bold target line for quotas, budget thresholds or pass marks.

## 6. Data Preparation

- **Scan Data:** Finds missing values, duplicates and numeric type issues.
- **Fill Missing:** Uses mean for numeric fields and mode for text fields.
- **Remove Duplicates:** Keeps the first exact duplicate row only.
- **Trim Spaces:** Removes leading/trailing text spaces.
- **Standardise Casing:** Converts text to Title Case.
- **Search & Replace:** Fixes category typos and naming inconsistencies.
- **Data Binning:** Converts numeric values into grouped range labels.
- **Inline Editing:** Double-click a preview cell, edit it, press Enter, and charts update.

## 7. Statistics

The Statistics tab computes count, mean, median, standard deviation, variance, min, max, quartiles, skewness, IQR outliers and Pearson correlation matrix. Results can be exported as CSV.

## 8. Pivot Table

Build cross-tab summaries with row field, column field, value field and aggregation. It includes totals and optional heatmap colouring, then exports to CSV.

## 9. Dashboard

Dashboards support chart panels, KPI cards, sparklines, drill-down filtering, global filters, layout switching, PNG export and v8 full-screen presentation mode.

## 10. Report Builder

Create a professional report from chart image, insights, statistics and pivot table. Export as standalone HTML or print/save as PDF.

## 11. Smart Narrative — No AI API

The narrative engine is rule-based. It calculates totals, averages, highest/lowest categories, spread, coefficient of variation, trend slope and top categories, then writes a deterministic plain-English summary.

## 12. Save and Load Workspace

The Save button exports a JSON workbook containing data, sheets, formulas, filters, dashboard and settings. Load restores the full session.

## 13. Deployment Summary

Recommended free deployment: GitHub Pages or Netlify. The app is static, so deployment means hosting `index.html`. See `DEPLOYMENT.md` for exact steps.

## 14. Ask Data — Local Natural-Language Query

Ask Data accepts simple local questions such as “top sales by region” or “average score by class”. It identifies fields from the dataset headers, selects an aggregation, returns a ranked answer and can apply the result to the worksheet. It is rule-based and does not call an AI API.

## 15. Sample Data and Data Dictionary

The menu strip includes **Sample Data** and **Dictionary**. Sample Data loads a built-in sales CSV directly in browser memory so users can test the simulator immediately. Dictionary creates a metadata profile for each field: data type, role, missing count, distinct count and examples. The dictionary can be exported as CSV.

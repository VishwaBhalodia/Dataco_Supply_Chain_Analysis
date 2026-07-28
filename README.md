# Supply Chain & Delivery Performance Analysis — DataCo Global

End-to-end data analytics project analysing ~180,000 orders to find the root causes of late deliveries and their impact on profitability — from raw data cleaning to an interactive Power BI dashboard.

## Tech Stack
`Excel` · `Power Query` · `VLOOKUP` · `Pivot Tables` · `Power BI` · `DAX`

## Key Findings
- **Premium modes are least reliable** — First Class is late 95% of the time vs 38% for Standard Class.
- **Lateness is systemic, not geographic** — uniform (~55%) across all regions.
- **No margin trade-off** — profit per order is flat (~$22) across all modes.
- **Profit is concentrated** in a few categories (Fishing, Cleats, Camping).
- **The problem is chronic** — the ~55% late rate persists across 2015–2018 with no improvement.

**KPIs:** 54.83% late delivery rate · $3.97M profit · 181K orders · $36.78M sales

## Workflow
Raw → Cleaned → Enriched → Modelled → Visualised
1. Profiled & cleaned the data (fixed date formats, removed PII/redundant columns) in Excel + Power Query.
2. Enriched orders with a Service Tier mapping via VLOOKUP.
3. Explored with pivot tables (late rate by mode/region, profit by mode).
4. Built a Power BI dashboard with 7 DAX measures.

## Repository
1. DataCo_Supply_Chain_Analysis.pbix	- Interactive Power BI dashboard
2. DataCo_Supply_Chain_Analysis_Sample.xlsx - Cleaned data sample with pivot tables and lookup table
3. DataCo_Report.pdf - Full analysis report (methodology, findings, dashboard)
4. DataCo_Problem_Statement.pdf - Business problem statement and deliverables

## Dataset
[DataCo Smart Supply Chain — Kaggle](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) (public, synthetic dataset used as a realistic simulation)

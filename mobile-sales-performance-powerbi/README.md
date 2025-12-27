
# Power BI Final Project: Mobile Sales Performance 2024

This project was developed as the final capstone for the Power BI class at Aptech Vietnam. 

The primary objective is to transform raw mobile sales data into actionable business insights, helping stakeholders track KPIs, identify growth opportunities, and optimize product distribution.

## Key Insights & Objectives
The dashboard addresses the following business questions:
- Revenue Growth: How has revenue trended month-over-month in 2024?
- Regional Performance: Which locations are exceeding sales targets?
- Product Analysis: Which mobile brands and models are the "Top Performers" vs "Slow Movers"?
  
## Tools

- Data Processing: SQL (Data extraction & transformation), Excel.
- Visualization: Power BI Desktop (Power Query, DAX, Data Modeling).
- Design: Custom color palettes and UI/UX principles for dashboards.

## Data

- Raw data files are stored in the `data/` folder.
- All datasets are in CSV format: Brand.csv, Location.csv, Sales.csv
  
## Key Features
- Advanced Data Modeling: Implemented a Star Schema with optimized relationships between Sales, Brand, and Location tables for efficient querying.
- Dynamic Analytics: Integrated Slicers for Time, Region, Brand and Product Model combined with Advanced DAX measures (YTD, YoY Growth, and Ranking) for real-time performance tracking.
- Granular Deep-Dives: Utilized Decomposition Trees to manually break down revenue metrics across multiple dimensions (Brand, Location, Product) to identify root causes.
- Demographic & Regional Analysis: Developed Heatmaps to correlate revenue with customer age groups. Created comparative visuals to contrast customer purchasing behavior and sales performance across different countries.

## Visual

Full dashboard visuals and analysis are exported to a PDF format for easy viewing:
👉 **[View Dashboard Report (PDF)](./screenshots/dashboard-overview.pdf)**

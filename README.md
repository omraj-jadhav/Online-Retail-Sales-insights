# Online Retail Sales Analysis — Excel Dashboard Project

## Overview

This project is an end-to-end sales analysis of an online retail dataset, built entirely in **Microsoft Excel**. It covers the full analytics workflow — from raw data cleaning to an interactive dashboard and written business insights — and is designed to demonstrate practical data analyst skills for a portfolio audience.

The workbook takes a raw transactional retail dataset and transforms it into a structured, decision-ready reporting tool, using Power Query for data cleaning, PivotTables and PivotCharts for analysis, and slicers/timelines for interactivity.

## Business Objective

The goal of this project is to help a hypothetical online retail business understand:

- How much revenue is being generated and how it trends over time
- Which products and countries drive the most sales
- How invoice-level activity (order volume, average order value) behaves
- Where the business is concentrated (domestic vs. international) and what that means for growth opportunities

The final deliverable is a single interactive Excel workbook that a business stakeholder could open and explore without needing to write a single formula.

## Dataset Description

The project uses an online retail transactional dataset containing invoice-level order records, including fields such as invoice number, product description, quantity, unit price, invoice date, customer ID, and country.

- **Total Revenue:** $10.6M
- **Total Invoices:** 19,960
- **Average Invoice Value:** $533.17
- **Countries Served:** 38
- **Domestic Sales Share:** 90%
- **International Sales Share:** 10%

> **Note on data completeness:** The dataset's final month (December 2011) contains a partial month of transactions rather than a full calendar month. Any apparent drop in sales during this period reflects incomplete data collection for that month, not an actual decline in business performance, and should not be interpreted as a trend without further context.

## Tools Used

- **Microsoft Excel** — sole tool used for the entire project
- **Power Query** — data import, cleaning, and transformation
- **PivotTables** — aggregation and summarization of cleaned data
- **PivotCharts** — visual representation of pivoted data
- **Slicers & Timeline** — interactive filtering by category, country, and date
- **Dashboard design** — consolidated single-page reporting view
- **Manual business insight writing** — interpretation of results into narrative recommendations

## Workbook Structure

The workbook is organized into the following sheets:

| # | Sheet Name | Purpose |
|---|------------|---------|
| 1 | `Online Retail Raw Data` | Original, unmodified source dataset |
| 2 | `Clean Sales Data` | Cleaned and standardized dataset (post Power Query) |
| 3 | `Customer Sales Data` | Sales data aggregated/structured at the customer level |
| 4 | `Sales by Country` | Sales data aggregated/structured by country |
| 5 | `Invoice Summary` | Invoice-level summary metrics |
| 6 | `Pivots` | PivotTables used to drive dashboard visuals |
| 7 | `Dashboard` | Final interactive dashboard |
| 8 | `Insights & Trends` | Written business insight reports |

This structure separates raw data, cleaned data, analysis, and reporting into distinct sheets, keeping the workbook easy to audit and navigate.

## Data Cleaning Process

Data cleaning was performed using Power Query and included steps such as:

- Removing records with missing or invalid customer/invoice information
- Standardizing product descriptions and country names
- Correcting data types (dates, numeric fields)
- Removing duplicate or clearly erroneous entries
- Structuring the cleaned output into a consistent table format ready for pivoting

The cleaned dataset feeds all downstream PivotTables, the dashboard, and the insight reports.

## Dashboard Features

The final dashboard consolidates the key metrics and trends into a single interactive view, including:

- **KPI summary cards** for total revenue, total invoices, and average invoice value
- **Revenue trend chart** showing sales performance over time
- **Country-level sales breakdown**, highlighting the domestic vs. international split
- **Top products view**, showing the highest-contributing items by sales
- **Slicers** for filtering by country and product
- **Timeline control** for filtering by invoice date range

All dashboard visuals are driven directly by the PivotTables on the `Pivots` sheet, so the dashboard updates dynamically when slicers or the timeline are adjusted.

## Key Insights

- **Revenue performance:** The business generated **$10.6M** in total revenue across **19,960 invoices**, with an average invoice value of **$533.17**.
- **Geographic concentration:** The business is heavily concentrated in its home market, with **90% of sales domestic** and only **10% international**, despite serving **38 countries** in total. This indicates a large but thin international footprint.
- **Product concentration:** Sales are notably concentrated in a small set of products. **DOTCOM POSTAGE**, **REGENCY CAKESTAND 3 TIER**, **PAPER CRAFT**, and **LITTLE BIRDIE** together account for **47% of total sales**, meaning nearly half of revenue depends on just four items.
- **Seasonality:** Sales activity shows a clear peak leading into the November period, consistent with pre-holiday purchasing behavior, before tapering off in the incomplete final month of the dataset (see data completeness note above).

## Business Recommendations

Based on the analysis, the following recommendations are proposed:

1. **Diversify the product mix carefully.** With four products driving 47% of sales, the business is exposed to concentration risk. Consider promoting mid-tier products to reduce dependency on top performers.
2. **Evaluate international growth potential.** With 38 countries served but only 10% of sales coming from international markets, there may be room to grow international demand through targeted marketing or logistics improvements — though this would require further investigation beyond this dataset.
3. **Plan inventory and staffing around peak season.** The pre-holiday sales peak suggests operational planning (inventory, fulfillment capacity) should be aligned with this seasonal pattern.
4. **Treat the final month's data with caution.** Since December 2011 data is incomplete, any performance reporting or forecasting that includes this period should account for the partial data rather than reading it as a genuine downturn.

## Skills Demonstrated

- Data cleaning and transformation using **Power Query**
- Data aggregation and summarization using **PivotTables**
- Data visualization using **PivotCharts**
- Building interactive, filterable reports using **Slicers** and a **Timeline**
- Designing a consolidated, stakeholder-ready **dashboard** in Excel
- Translating raw analysis into **written business insights and recommendations**
- Structuring a multi-sheet workbook in a clear, auditable, end-to-end analytical workflow

## Conclusion

This project demonstrates a complete Excel-based analytics workflow — from raw data to a cleaned dataset, through PivotTable analysis, to a final interactive dashboard supported by written business insights. It reflects practical, real-world data analyst skills using tools that are widely used in business environments, and is intended as a portfolio piece to showcase those capabilities to recruiters and hiring managers.

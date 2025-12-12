# Adidas-sales-Analise
Nice — here’s a ready-to-use README.md you can drop into your new GitHub repo. It’s tailored for the interactive Adidas sales dashboard shown in your image (an Excel-based sales dashboard). Copy the whole block below into your repository as README.md and adjust any details (paths, names, dataset) as needed.

# Adidas US Interactive Sales Dashboard

![Dashboard screenshot](./images/adidas-dashboard.png)

**Live interactive sales dashboard** built in Microsoft Excel to visualize Adidas US sales by product, region, city, retailer and sales method. The dashboard includes slicers, pivot charts, a US sales map, and summary KPIs.

---

## Table of contents

- [Project overview](#project-overview)  
- [Features](#features)  
- [Files in this repo](#files-in-this-repo)  
- [Installation / Setup](#installation--setup)  
- [How to use](#how-to-use)  
- [Data format / columns](#data-format--columns)  
- [Suggested improvements](#suggested-improvements)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## Project overview

This repository contains an Excel workbook and supporting files for an interactive sales dashboard that helps analyze Adidas US sales. It provides quick insights into units sold, operating profit, sales method distribution, top products and regions — and allows filtering by state and city using slicers.

---

## Features

- KPI header with total units sold, total profit and number of retailers
- Product profit bar chart (profit per product)
- Sales method breakdown (pie chart)
- Retailer/product horizontal bar chart
- US map shaded by sales region
- Slicers for `State` and `City` for fast interactive filtering
- Clean, presentation-ready layout suitable for stakeholder briefings

---

## Files in this repo



/ (root)
├─ README.md
├─ data/
│ └─ adidas_sales.csv # source CSV used to populate the dashboard
├─ workbook/
│ └─ adidas_dashboard.xlsx # main Excel workbook (PivotTables, charts, slicers)
├─ images/
│ └─ adidas-dashboard.png # screenshot used in this README
└─ LICENSE


> If you have the original screenshot located elsewhere, place it at `images/adidas-dashboard.png` so it displays above.

---

## Installation / Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/adidas-sales-dashboard.git
   cd adidas-sales-dashboard


Open the Excel workbook:

Open workbook/adidas_dashboard.xlsx with Microsoft Excel (Excel 2016 or later recommended).

Alternatively, open the CSV data/adidas_sales.csv in Excel and recreate the PivotTables/Charts if the workbook is not included.

If the workbook uses Power Query or external connections:

Enable connections and refresh the data (Data → Refresh All).

How to use

Open adidas_dashboard.xlsx.

On the dashboard sheet you will find:

Slicers (left side) for State and City. Click items to filter all charts.

Top banner with KPIs (units sold, profit, retailers).

Charts: product profit, sales method pie, top retailers, and a US map by sales region.

To refresh after updating the source:

Data → Refresh All (or right-click pivot tables → Refresh).

To edit chart appearance or KPIs:

Right-click the chart or pivot table → Format Chart / PivotTable Options.

Data format / columns

The dashboard expects a flat table (CSV/XLSX) with at least the following columns:

OrderID (or TransactionID) — optional but helpful

Date — date of sale (YYYY-MM-DD)

State — US state (used by slicer and map)

City — city (used by slicer)

Product — product name or category (e.g., MEN'S APPAREL)

Retailer — retailer name (e.g., Walmart, Foot Locker)

SalesMethod — In-store / Online / Outlet (used in pie chart)

UnitsSold — integer (used for units KPI & aggregation)

Profit — numeric (operating profit per row)

PricePerUnit — numeric (optional)

If your dataset contains different column names, update the PivotTable source ranges and mapping in the workbook.

Suggested improvements

Convert to Power BI for richer mapping and sharing (Power BI Service).

Add drill-through detail sheets for individual orders or retailer-level reports.

Add time-slicer (Year / Quarter / Month) for trend analysis.

Add forecasting or YoY comparisons using DAX (Power BI) or Excel Forecast functions.

Make the map interactive using Mapbox or ESRI layers (if migrating to a web dashboard).

Contributing

Contributions are welcome! To contribute:

Fork the repo.

Create a feature branch: git checkout -b feature/my-change

Commit your changes: git commit -m "Add feature"

Push to your branch: git push origin feature/my-change

Open a pull request describing your changes.

Please include a sample dataset (sanitized) when adding features that require data.

License

This project is licensed under the MIT License. See LICENSE for details.

Contact

Maintainer: Your Name — replace with your GitHub profile or email.

Quick tips

Put the dashboard screenshot in images/adidas-dashboard.png so it renders in the README.

If you want I can generate a concise LICENSE file and a short CONTRIBUTING.md for the repo.
dashbord
<img width="982" height="482" alt="adidas2025-12-12 142331" src="https://github.com/user-attachments/assets/022a7e8d-cb66-4851-930e-9ad60a1b5e64" />



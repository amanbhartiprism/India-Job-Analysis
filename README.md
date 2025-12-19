# Indian Job Market Analysis Dashboard (2015-2025)

![Dashboard Preview](dashboard_screenshot.png)

## Project Overview

This interactive Excel dashboard is designed to analyze a decade of hiring data across India, providing a clear picture of market trends for job seekers and professionals. By transforming raw data into a dynamic and user-friendly interface, it allows users to instantly explore key metrics like salary benchmarks, city-specific demand, top employers, and the prevalence of remote work for various job roles. The project is built on a robust, professional "Engine-Processing-Dashboard" architecture to ensure accurate, real-time calculations.

## Key Features

* **Interactive Filtering:** Use dropdowns for **Job Role**, **City**, and **Year** to slice the data and update the entire dashboard instantly.
* **Dynamic KPIs:** Get real-time insights into **National Average Salary**, the selected city's **Demand Share**, and the **Yearly Job Count**.
* **Trend Analysis:** Visualize hiring volume trends over the last decade with an auto-updating line chart.
* **Regional Comparison:** A dual-axis chart compares average salaries and job totals across different regions of India.
* **Top Company Insights:** See the top 5 companies currently hiring for your selected role and city.
* **Work Type Distribution:** A doughnut chart clearly shows the split between **Remote** and **On-site** job opportunities.

## How to Use

Simply select your desired criteria from the three dropdown menus at the top of the dashboard: **Job Role**, **City**, and **Select Year**. All charts, graphs, and key performance indicators (KPIs) will automatically refresh to display data relevant to your selection.

## Technical Highlights

* Utilizes advanced **Excel Dynamic Array** functions (`FILTER`, `SORT`, `UNIQUE`, `TAKE`) for powerful data manipulation.
* Implements a structured **multi-tier architecture** (Raw Data $\rightarrow$ Processing $\rightarrow$ Engine $\rightarrow$ Dashboard) for clean logic separation.
* Features a professional, locked UI/UX design to prevent accidental errors while remaining fully interactive.

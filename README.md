# Amazon Sales Dashboard - Power BI

## Project Overview

This Power BI dashboard provides a comprehensive analysis of Amazon sales data, offering key insights into sales performance, customer behavior, and product trends. The goal of this project is to empower stakeholders to make data-driven decisions by visualizing complex sales data in an intuitive and interactive manner.

## Features

This dashboard offers the following key analytical capabilities, based on the provided Amazon sales data:

* **Overall Sales Performance:** Track total sales, revenue, profit, and quantity sold over time.
* **Sales by Product Category:** Identify top-performing and underperforming product categories.
* **Product Performance:** Monitor individual product sales based on `Price(Dollar)` and analyze product popularity through `Number of reviews`.
* **Order and Shipment Analysis:** Gain insights into `Shipment` details.
* **Time-based Trends:** Explore sales trends by `Order Date`.
* **Interactive Filters:** Drill down into specific data points using slicers for date ranges, categories, etc.

## Data Source

The dashboard is built using a dataset containing Amazon sales information.
* **File Name:** `Amazon_Combined_Data.xlsx - Amazon_Data.csv`
* **File Type:** CSV
* **Key Columns:** `Product Category`, `Product Description`, `Price(Dollar)`, `Number of reviews`, `Shipment`, `Order Date`.
* **Data Period:** From `2019-01-03` to `2022-04-30` (based on the `Order Date` column snippets).

## Technologies Used

* **Microsoft Power BI Desktop:** For data loading, transformation (Power Query), data modeling (Power Pivot), and visualization.

## Getting Started

To view and interact with this Power BI dashboard, follow these steps:

1.  **Prerequisites:** Ensure you have **Microsoft Power BI Desktop** installed on your system. You can download it for free from the [official Microsoft Power BI website](https://powerbi.microsoft.com/desktop/).
2.  **Download Project Files:**
    * If hosted on GitHub: Clone this repository: `git clone [Your GitHub Repo URL]`
    * If provided as a file: Download the `[Your_Dashboard_Name].pbix` file.
3.  **Open the Dashboard:**
    * Launch Power BI Desktop.
    * Go to `File` > `Open report` and navigate to the downloaded (https://github.com/praneethsaiD/AMAZON_SALES_DASHBOARD/blob/main/Amazon%20sales%20Dashboard.pbix) file.
4.  **Data Refresh (if applicable):**
    * If the data source is not embedded or requires a refresh, Power BI might prompt you to provide credentials or confirm the data source location.
    * To manually refresh data, go to `Home` tab > `Refresh`.

## Dashboard Structure

The Power BI file (`.pbix`) contains:

* **Data Model:** Defines relationships between tables and calculated measures (DAX).
* **Power Query Editor:** Contains the steps for data extraction, transformation, and loading (ETL) of the `Amazon_Data.csv` file.
* **Report Pages:** Multiple pages visualizing different aspects of the sales data.

## Usage

* **Interactivity:** Click on visuals, use slicers, and drill-down buttons to explore data at different levels of detail.
* **Filters:** Utilize the filter pane to apply specific filters and customize your view.
* **Tooltips:** Hover over data points to see additional details in tooltips.

## Contact

For any questions or feedback, please contact:

Name: Donthireddy Praneeth Sai Durga Reddy
Linkedin: www.linkedin.com/in/donthireddy-praneeth-sai-durga-reddy



---

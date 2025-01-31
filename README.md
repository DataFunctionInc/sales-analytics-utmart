# UT Mart Sales Analytics – Tableau Dashboard

## Project Overview

The **UT Mart Sales Analytics Dashboard** is a comprehensive data visualization tool designed to track and analyze key business metrics for a retail environment. This dashboard provides real-time insights into sales, profit, and quantity sold, segmented by product category, region, and time period.

The dashboard is built using Tableau to facilitate interactive data exploration and decision-making based on historical and current sales performance data. The system is designed to be highly customizable, allowing users to filter and drill down on key metrics.

## Features

- **Sales Overview:** Displays total sales, profit, and quantity sold by selected time periods (monthly, quarterly, yearly).
- **Category Performance:** Provides insights into sales and profit performance by product category.
- **Region Analysis:** Breaks down sales and profit data by geographic region.
- **Customer Purchase Patterns:** Analyzes customer behavior, including the average number of items purchased per order.
- **Profit Calculation:** Automatically calculates profit based on the assumption that profit is 30% of the selling price.
- **Dynamic Filters:** Users can filter data by different time periods, regions, and product categories for deeper analysis.

## Technologies Used

- **Tableau:** Data visualization and dashboard creation tool.
- **Data Source:** CSV files containing sales transaction data.
- **Data Security:** Data is secured via Tableau's built-in permission management features.

## System Requirements

- **Tableau Desktop** or **Tableau Public** for development and local visualization.
- **Tableau Server** or **Tableau Online** for production deployment (for sharing and accessing the dashboard online).
- Supported browsers: Chrome, Firefox, Safari (for Tableau Server or Online access).

## Data Flow

1. **Data Ingestion:** Data is imported from CSV files containing transactional sales information, including sales, profit, and quantities sold.
2. **Data Preparation:** The data is cleaned and structured within Tableau, ensuring accuracy in visualizations and calculations (e.g., profit margin).
3. **Visualization Development:** The dashboard is created using Tableau’s drag-and-drop interface, with measures and dimensions mapped to the required KPIs.

## Usage Instructions

1. **Accessing the Dashboard:**

   - Stakeholders can access the dashboard via the Tableau Server or Tableau Online link.
   - The dashboard is interactive; users can filter data by different time periods (months, years), product categories, and regions.

2. **Interacting with the Dashboard:**
   - **Filters:** Use the dropdowns or slicers to filter the data by time period, product category, and region.
   - **Drill Down:** Click on any chart or graph to drill down into more granular data for deeper analysis.
   - **Tooltips:** Hover over any data point for additional information.

## Maintenance & Support

1. **Data Refresh Schedule:**

   - Data refresh schedules should be established to ensure that the dashboard reflects the most current data.
   - Set up daily, weekly, or monthly refresh intervals based on data volume and business needs.

2. **Troubleshooting:**

   - If data is not updating, verify the connection to the data source and ensure that the refresh schedule is working correctly.
   - For issues with the visualizations, check for broken fields or missing data.

3. **User Access Management:**

   - Maintain an updated list of users who have access to the dashboard.
   - Ensure that user permissions are properly set for viewing, editing, or downloading the reports.

4. **Performance Monitoring:**
   - Monitor dashboard load times and performance. If necessary, optimize data sources by using extracts instead of live connections, or aggregating large datasets.

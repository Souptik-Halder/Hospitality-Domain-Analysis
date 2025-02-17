# Hospitality Domain Analysis Dashboard
## DASHBOARD LINK- https://app.powerbi.com/groups/me/reports/8e90d8c2-119b-4d20-974e-3afaf3b78a00/1964a540209ba2444d78?experience=power-bi
This repository contains the files for a Power BI dashboard designed to analyze key performance indicators (KPIs) within the hospitality domain. The dashboard provides insights into revenue, occupancy, average daily rate (ADR), and other metrics, allowing stakeholders to make data-driven decisions to optimize performance and profitability.

## Overview

The dashboard leverages data visualization techniques to present a comprehensive view of the business, enabling users to:

*   **Track Realisation % and ADR by Booking Platform:** Identify the most profitable booking channels.
*   **Analyze Revenue by Category:** Understand the contribution of Luxury and Business categories.
*   **Monitor RevPar, ADR, and Occupancy % by Month and Week:**  Observe trends over time and identify seasonal patterns.
*   **Filter Data:** Analyze the data based on city and room type.
*   **Examine Detailed Property Performance:** View granular performance data for individual properties.

## Key Features and Visualizations

The dashboard includes the following key features and visualizations:

*   **Date Range Selection:** Allows users to filter data based on specific time periods (May 2022 - Jul 2022).
*   **Realisation % and ADR by Booking Platform:**
    *   A combination chart displaying Realisation % as a line graph and ADR as bar graphs, broken down by different booking platforms (e.g., logtrip, journey, direct online, etc.).
    *   Helps identify which platforms are generating the most bookings and revenue.
*   **Revenue by Category:**
    *   A donut chart showing the proportion of revenue generated by different room categories (Luxury and Business).
    *   Reveals the relative importance of each category to overall revenue.
*   **RevPar, ADR, and Occupancy % by Month and Week:**
    *   Line charts illustrating the trends of RevPar, ADR, and Occupancy % over time (May 2022 - July 2022), broken down by week number.
    *   Helps to identify seasonal trends and performance fluctuations.
*   **Filtering Capabilities:**
    *   Dropdown filters allowing users to select specific cities and room types to refine the analysis.
    *   Enables targeted insights for specific regions or room categories.
*   **Key Performance Indicators (KPIs):**
    *   Visual display of core KPIs such as Realisation %, Occupancy %, RevPar, ADR, DSRN, and Total Revenue.
*   **Property Performance Table:**
    *   A tabular view presenting detailed performance data for individual properties, including:
        *   `property_id`
        *   `property_name`
        *   `city`
        *   `revenue`
        *   `RevPar`
        *   `occupancy %`
        *   `ADR`
        *   `DSRN`
        *   `DBRN`
        *   `DURN`
        *   `Realisation %`
        *   `Cancellation %`
        *   `Avg Rating`
*  **Total metrics**
   * Aggregated sum of key measures

## Data Sources

*   The dashboard is populated using a tabular data source which contains properties data like name, city, revenue, and other performance KPIs.  The data is contained in the table in the dashboard, but its source is unspecified.

## SNAP → ![Image](https://github.com/user-attachments/assets/8e7fe944-0b61-4641-831f-d0d7fe2c901a)

## Usage

1.  **Open the Power BI file:** Open the dashboard in Power BI Desktop.
2.  **Interact with Visualizations:** Click on different elements within the visualizations to filter and explore the data.
3.  **Use Filters:** Utilize the "FILTER BY CITY" and "FILTER BY ROOM TYPE" dropdowns to focus on specific subsets of the data.
4.  **Analyze KPIs:** Observe the key performance indicators to understand overall business performance and identify areas for improvement.
5.  **Examine Property Table:** Review the property-level data in the table to identify high-performing and underperforming properties.
6.  **Analyze Trendlines:** Review weekly trendlines to identify seasonal patterns and potential issues.

## Possible Improvements

*   **Data Refresh Automation:** Set up automated data refreshes to ensure the dashboard always displays the most up-to-date information.
*   **Interactive Drill-Downs:** Add interactive drill-downs to allow users to explore the data at a more granular level.
*   **Forecasting:** Integrate forecasting models to predict future performance based on historical trends.
*   **Custom Alerts:** Configure custom alerts to notify stakeholders when key metrics fall outside of acceptable ranges.
*   **Data from different sources:** Connect the dashboard to multiple data sources to enrich the analysis and create a more holistic view of the business.
*   **Detailed Booking Platform Breakdown:** Expand the booking platform analysis to include more detailed metrics for each platform, such as customer acquisition cost and conversion rates.

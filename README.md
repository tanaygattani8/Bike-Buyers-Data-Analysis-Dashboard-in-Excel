
# Bike Buyers Data Analysis & Dashboard in Excel

This project presents a comprehensive analysis of a dataset of bike buyers to uncover key demographic and socio-economic factors influencing purchasing decisions. The primary outcome is an interactive dashboard created entirely within Microsoft Excel, designed to provide at-a-glance insights for marketing and sales teams.


The interactive dashboard brings the data to life, allowing users to dynamically filter and explore customer segments.

## 💡 Key Questions & Insights

This analysis and the resulting dashboard were designed to answer critical business questions, such as:

  * **Income Disparity**: What is the average income of customers who purchased a bike versus those who did not?
  * **Commute Impact**: Is there a correlation between a customer's commute distance and their likelihood of purchasing a bike?
  * **Age Demographics**: Which age groups are most likely to purchase a bike?
  * **Regional Trends**: Are there specific geographic regions with higher purchase rates?
  * **Customer Profile**: What is the typical profile of a bike buyer in terms of gender, marital status, and number of children?

## 📂 Project Structure

The Excel file (`Project.xlsx`) is organized into four main sheets:

1.  **bike\_buyers**: The raw, unprocessed dataset containing 1000 records of customer information.
2.  **Working Sheet**: The primary data preparation area where:
      * Data was cleaned and checked for inconsistencies.
      * New columns like "Age Brackets" were created using formulas to better categorize the data.
      * Categorical data was standardized for analysis.
3.  **Pivot Table**: This sheet contains all the pivot tables used as the calculation engine for the dashboard. It aggregates the data from the "Working Sheet" to summarize key metrics.
4.  **Dashboard**: The final, interactive visualization layer that presents the insights from the pivot tables in a user-friendly format with charts and slicers.

## 🛠️ Methodology & Tools

This project was developed entirely using **Microsoft Excel**. The process involved:

1.  **Data Cleaning & Preparation**: The raw data was cleaned in the `Working Sheet`. Formulas (e.g., `IF`, `VLOOKUP`) were used to create helper columns and ensure data quality.
2.  **Data Analysis with Pivot Tables**: Pivot tables were extensively used to aggregate the cleaned data, calculating averages, counts, and sums based on various dimensions like region, gender, and purchase decision.
3.  **Dashboard Visualization**: An interactive dashboard was built using:
      * **Pivot Charts**: To visually represent the aggregated data.
      * **Slicers**: To enable dynamic filtering of the dashboard by `Marital Status`, `Region`, `Education`, and other key demographics.
      * **Report Connections**: To link all slicers to the relevant pivot tables, ensuring the entire dashboard updates in unison.
-----

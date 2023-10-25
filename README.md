# Startup Expansion Data Analysis Project

![Startup Expansion Data Analysis](https://miro.medium.com/v2/resize:fit:1400/1*QHpTbnP_oDGKIcAHLwPp-A.png)

This project involves the analysis of a dataset related to the expansion of various startup stores. The data was explored and processed using Python, and the results were visualized in a Power BI dashboard. This readme file summarizes the project and its key findings.

## Project Overview

The project aims to provide insights into the performance and expansion strategies of startup stores based on their location, marketing spend, and revenue. The dataset used in this project contains information about multiple stores, including details such as city, state, sales region, expansion status, marketing spend, and revenue.

## Data Exploration and Preprocessing

- The project began with data exploration in Python, utilizing libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
- The dataset consists of 150 entries and 7 columns.
- Key statistics for the "Marketing Spend" and "Revenue" columns were calculated to understand the data distribution.

## Data Preprocessing

- Duplicate and missing values were checked, and the dataset was found to be clean with no duplicates or missing data.
- Categorical columns such as "City," "State," "Sales Region," and "New Expansion" were examined.
- "Sales Region" and "New Expansion" columns have limited unique values, indicating that they are suitable for categorical analysis.

## Data Visualization

- A random sample of 10 entries from the dataset was displayed to provide an overview of the data.
- A bar chart was generated to visualize the distribution of stores across different sales regions.

## Business Metrics Calculation

- Business metrics, such as profit and Return on Marketing Spend (ROMS), were calculated to understand the financial performance of each store.
- Profit was computed as the difference between revenue and marketing spend.
- ROMS was calculated as (profit / marketing spend) * 100.

## Data Export

- The modified dataset, including the calculated profit and ROMS, was exported to a CSV file named "startup-expansion-modified.csv."

## Power BI Dashboard

- The project included the creation of a Power BI dashboard named "startup-expansion.pbix" to visualize the dataset and explore the relationships between different columns.

## Key Insights

- The project revealed that most stores were in California, followed by Texas and Florida.
- The majority of stores were in Sales Region 2, and most were labeled as "Old" expansion.
- The ROMS metric highlighted the stores' return on marketing spend, which can be a crucial indicator of business performance.
- The Power BI dashboard offers an interactive platform for further exploration and analysis.

## Conclusion

This project provides a comprehensive analysis of startup store expansion data. It offers insights into the distribution of stores across regions, the impact of marketing spend on revenue, and the overall financial performance of the stores. The Power BI dashboard enhances data exploration and visualization capabilities, making it easier to uncover patterns and trends in the dataset.

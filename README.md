# COVID-19-Global
# COVID-19 Global Data Analysis Dashboard | Power BI

## Project Overview

This project analyzes global COVID-19 data using Microsoft Power BI to explore the spread of the pandemic, monitor confirmed cases and deaths, examine reported recoveries, and identify trends across countries and over time.

The dashboard transforms raw COVID-19 time-series data into interactive visualizations and key performance indicators (KPIs) to support data-driven exploration of the pandemic.

## Business Objectives

* Monitor global confirmed COVID-19 cases, deaths, and recoveries.
* Analyze the progression of the pandemic over time.
* Compare reported COVID-19 figures across countries and regions.
* Identify countries with high reported case and death counts.
* Present complex public-health data through an interactive dashboard.

## Tools and Technologies

* **Microsoft Power BI** — dashboard development and data visualization.
* **Power Query** — data cleaning, transformation, and preparation.
* **DAX** — measures, KPI calculations, and time-based analysis.
* **CSV datasets** — source data ingestion and preparation.

## Dataset

The project uses COVID-19 time-series datasets published by the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE).

The source files include:

* `time_series_covid19_confirmed_global.csv`
* `time_series_covid19_deaths_global.csv`
* `time_series_covid19_recovered_global.csv`

The datasets contain country and regional identifiers alongside date-based reported figures.

**Original data source:** [JHU CSSE COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19)

*Note: The original repository and dataset structure may have changed since the data was collected. The analysis should be interpreted in the context of the project's selected data snapshot.*

## Data Preparation

Power Query was used to prepare the source datasets for analysis. The workflow included:

* Importing the CSV files into Power BI.
* Promoting headers and standardizing column names.
* Reshaping date columns into a suitable time-series structure using unpivoting.
* Converting fields to appropriate data types.
* Preparing the confirmed cases, deaths, and recoveries data for analysis.
* Establishing a consistent structure for time-based and geographic comparisons.

## Dashboard Features

The dashboard was designed to include:

* **KPI cards:** Overall confirmed cases, reported deaths, and recoveries.
* **Time-series line charts:** Changes in reported COVID-19 figures over time.
* **Country comparison charts:** Comparison of reported cases and deaths across countries.
* **Geographic map:** Exploration of the geographic distribution of reported cases.
* **Donut or pie chart:** Proportional comparison of selected COVID-19 metrics.
* **Detailed data table:** Country-level figures for closer inspection.
* **Interactive slicers:** Filtering by available dates, countries, and regions.

## Analytical Approach

The analysis emphasizes time-series trends, geographic comparisons, and country-level differences. Since confirmed cases, deaths, and recoveries in the source datasets are cumulative measures, the KPI calculations must use the latest available reporting date in the selected dataset rather than summing cumulative values across all dates.

This distinction helps prevent double-counting when reporting cumulative totals.

## Key Skills Demonstrated

* Data cleaning and transformation with Power Query.
* Data modeling and date-based analysis.
* DAX measures and KPI development.
* Time-series analysis.
* Geographic data visualization.
* Interactive dashboard design.
* Translating raw data into accessible visual insights.

## Project Deliverables

* Power BI dashboard (`.pbix`).
* Dashboard screenshots.
* Project documentation and analysis report.
* Demonstration video, where available.

## Conclusion

This project demonstrates the use of Power BI to transform raw global COVID-19 time-series data into an interactive analytical dashboard. It highlights practical skills in data preparation, data modeling, KPI development, and visualization while making pandemic trends easier to explore across time and geography.
